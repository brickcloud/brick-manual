Overview
=====

|
1990년대 VMware같은 하이퍼 바이저 기반의 가상화 기술의 등장은 IT Infra 지형을 크게 바꾸어 놓았습니다.
최근에는 컨테이너(Container)라고 불리는 OS 레벨의 프로세스 가상화 기술이 등장하여,
또 다시 IT Infra의 지형을 크게 바꾸어 가고 있습니다.

컨테이너 기술은 기술적인 난이도와 복잡함 때문에 사용이 다소 어려운 부분이 있음에도,
컨테이너 기술이 가진 다양한 장점 때문에, 
최근에는 인공지능(머신러닝) 개발을 위한 플랫폼에 많이 사용되고 있습니다.


Container Feature
----------------

**빠른 어플리케이션 배포**
**어플리케이션의 이식성**
**버전 제어, 컴포넌트 재사용**
**유지관리의 용이성**




To use Lumache, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lumache

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

