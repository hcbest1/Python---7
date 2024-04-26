# Python---7

{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyNPoJsDzJm/K1TTZhQjPZ19",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/ciellleen/copyright/blob/main/7%EC%9D%BC%EC%B0%A8\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": 1,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "hrsymV3xHYh-",
        "outputId": "d7e739ae-5e71-4b14-dfbe-85e1660d387e"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "13\n"
          ]
        }
      ],
      "source": [
        "#len() : Returns the length of the string\n",
        "a = 'I Love Python'\n",
        "print( len(a) )"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "name = 'BlockDMask'\n",
        "phone = '010 xxxx xxxx'\n",
        "address = 'korea'\n",
        "print(len(name)) # 10\n",
        "print(len(phone)) # 13\n",
        "print(len(address)) # 5"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "kYpEwFD-HfJN",
        "outputId": "93b20726-52ba-46ee-827e-7e91b51e1978"
      },
      "execution_count": 4,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "10\n",
            "13\n",
            "5\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# =========================================================\n",
        "# min(iterable) 함수 예제1 : 리스트 이용\n",
        "a = [1, 2, 3]\n",
        "print(min(a)) # 반환 : 1\n",
        "\n",
        "# =========================================================\n",
        "# min(iterable) 함수 예제2 : 문자열 이용\n",
        "b = 'BlockDMask'\n",
        "print(min(b)) # 반환 : 'B'\n",
        "\n",
        "# =========================================================\n",
        "# min(iterable) 함수 예제4 : 튜플 이용\n",
        "d = (6, 5, 4, 2)\n",
        "print(min(d)) # 반환 : 2\n",
        "\n",
        "# =========================================================\n",
        "a = [1,2,3]\n",
        "b = [1,2,4]\n",
        "print(min(a,b)) # 반환: [1,2,3]\n",
        "\n",
        "# =========================================================\n",
        "c = 'CC'\n",
        "d = 'BA'\n",
        "print(min(c,d)) # 반환: BA\n",
        "\n",
        "# =========================================================\n",
        "# min(arg1, arg2, ...) 함수 예제4 : 인자가 N 개\n",
        "g = [2, 3, 4]\n",
        "h = [2, 2, 2, 2, 2]\n",
        "i = [9, 8, 7, 6, 5]\n",
        "j = [1]\n",
        "k = [0]\n",
        "print(min(g, h, i, j, k)) # 반환 : [0]\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "oSr8iO-RHfMu",
        "outputId": "8aba058b-6f68-4e12-ce3c-5ba460bb2b44"
      },
      "execution_count": 6,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "1\n",
            "B\n",
            "2\n",
            "[1, 2, 3]\n",
            "BA\n",
            "[0]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "myString = \"everdevel\"\n",
        "print(myString.count('e'))\n",
        "\n",
        "# 문자열 'BlockDMask' 선언\n",
        "a = 'BlockDMask'\n",
        "\n",
        "# 문자열에서 'k'가 몇개 있는지 ?\n",
        "print(\"#1 a.count('k')\")\n",
        "print(a.count('k'))\n",
        "\n",
        "# 문자열에서 'DM'가 몇개 있는지 ?\n",
        "print(\"#2 a.count('DM')\")\n",
        "print(a.count('DM'))\n",
        "\n",
        "# 문자열에서 특정 범위 내부에 'k' 가 몇개 있는지?\n",
        "# B l o c k D M a s k 에서 index를 표기해보면\n",
        "# 0 1 2 3 4 5 6 7 8 9 입니다.\n",
        "print(\"#3 a[2] + ' ~ ' + a[4]\")\n",
        "print(a[2] + ' ~ ' + a[4])\n",
        "\n",
        "print(\"#4 a.count('k', 2, 3)\")\n",
        "print(a.count('k', 2, 3))\n",
        "\n",
        "print(\"#5 a.count('k', 2, 4)\")\n",
        "print(a.count('k', 2, 4))\n",
        "\n",
        "print(\"#6 a.count('k', 2, 5)\")\n",
        "print(a.count('k', 2, 5))"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "oXzcC0M2HfPe",
        "outputId": "0f3a47fb-4e2a-48b3-9681-0957aa4784f0"
      },
      "execution_count": 10,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "4\n",
            "#1 a.count('k')\n",
            "2\n",
            "#2 a.count('DM')\n",
            "1\n",
            "#3 a[2] + ' ~ ' + a[4]\n",
            "o ~ k\n",
            "#4 a.count('k', 2, 3)\n",
            "0\n",
            "#5 a.count('k', 2, 4)\n",
            "0\n",
            "#6 a.count('k', 2, 5)\n",
            "1\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "str_value = \"BlockDMask Blog.\"\n",
        "print(f\"str : {str_value}\\n\")\n",
        "\n",
        "# find 예제1\n",
        "print(\"1. str.find('찾을 문자')\")\n",
        "result1 = str_value.find('a')\n",
        "\n",
        "# 문자가 있는 경우\n",
        "result2 = str_value.find('Z')\n",
        "\n",
        "# 문자가 없는 경우\n",
        "print(f\"str.find('a') : {result1}\")\n",
        "print(f\"str.find('Z') : {result2}\")\n",
        "\n",
        "result3 = str_value.find('ask')\n",
        "# 문자열이 있는 경우\n",
        "result4 = str_value.find('kkk')\n",
        "# 문자열이 없는 경우\n",
        "print(f\"str.find('ask') : {result3}\")\n",
        "print(f\"str.find('kkk') : {result4}\")\n",
        "print()\n",
        "\n",
        "# find 예제2\n",
        "print(\"2. str.find('찾을 문자', 시작index)\")\n",
        "result5 = str_value.find('o')\n",
        "result6 = str_value.find('o', 5)\n",
        "\n",
        "print(f\"str.find('o') : {result5}\")\n",
        "print(f\"str[5] : {str_value[5]}\")\n",
        "print(f\"str.find('o', 5) : {result6}\")\n",
        "print()\n",
        "\n",
        "# find 예제3\n",
        "print(\"3. str.find('찾을 문자', 시작 index, 끝 index)\")\n",
        "result7 = str_value.find('o')\n",
        "result8 = str_value.find('o', 5, 11)\n",
        "\n",
        "# \"DMask B\"\n",
        "print(f\"str.find('o') : {result7}\")\n",
        "print(f\"str[5]~str[11] : {str_value[5]} ~ {str_value[11]}\")\n",
        "print(f\"str.find('o', 5, 11) : {result8}\")\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "8lN0H_8QHfSG",
        "outputId": "3c77b938-e314-4dd0-e1bd-be4d5179a12a"
      },
      "execution_count": 14,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "str : BlockDMask Blog.\n",
            "\n",
            "1. str.find('찾을 문자')\n",
            "str.find('a') : 7\n",
            "str.find('Z') : -1\n",
            "str.find('ask') : 7\n",
            "str.find('kkk') : -1\n",
            "\n",
            "2. str.find('찾을 문자', 시작index)\n",
            "str.find('o') : 2\n",
            "str[5] : D\n",
            "str.find('o', 5) : 13\n",
            "\n",
            "3. str.find('찾을 문자', 시작 index, 끝 index)\n",
            "str.find('o') : 2\n",
            "str[5]~str[11] : D ~ B\n",
            "str.find('o', 5, 11) : -1\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "str_value = 'Hello world, Python!'\n",
        "\n",
        "if str_value.startswith('Hello'):\n",
        "    print('It starts with Hello')\n",
        "\n",
        "if not str_value.startswith('Python'):\n",
        "    print('It does not start with Python')\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "FqRAwzAtHfW8",
        "outputId": "03dbac58-bf0d-44bb-a4db-93ca51e3d371"
      },
      "execution_count": 15,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "It starts with Hello\n",
            "It does not start with Python\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "str_value = \"this is string example....wow!!!\"\n",
        "\n",
        "suffix = \"wow!!!\"\n",
        "print(str_value.endswith(suffix))\n",
        "print(str_value.endswith(suffix, 20))\n",
        "\n",
        "suffix = \"is\"\n",
        "print(str_value.endswith(suffix, 2, 4))\n",
        "print(str_value.endswith(suffix, 2, 6))"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Nv4dviyfHfZU",
        "outputId": "88988c8e-8b71-4a54-be88-db5f875e531a"
      },
      "execution_count": 17,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "True\n",
            "True\n",
            "True\n",
            "False\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "text = 'Welcome to Codetorial'\n",
        "\n",
        "pos_e_last = text.rfind('e')\n",
        "print(pos_e_last)\n",
        "\n",
        "pos_e_first = text.find('e')\n",
        "print(pos_e_first)\n",
        "\n",
        "pos_to_last = text.rfind('to')\n",
        "print(pos_to_last)\n",
        "\n",
        "pos_to_first = text.find('to')\n",
        "print(pos_to_first)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "TMGL280BHfb3",
        "outputId": "34ecc8ab-4677-45cf-dfe7-fe3a6f9d20a0"
      },
      "execution_count": 18,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "14\n",
            "1\n",
            "15\n",
            "8\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = [123, 421, 212, 11, 24, 102, 29, 92, 10]\n",
        "print(a.index(212))\n",
        "# 리스트.index(x)\n",
        "# 데이터 x의 위치 반환\n",
        "nums_list = [1,2,3,3,3,5,6,8,9]\n",
        "nums_tuple = (1,2,3,3,3,5,6,8,9)\n",
        "nums_set = {1,2,3,5,6,8,9}\n",
        "\n",
        "print(nums_list.index(2))  # 1\n",
        "print(nums_list.index(3))  # 2\n",
        "# -> 찾고자하는 데이터가 여러개 존재할 경우, 가장 작은 위치 값 반환\n",
        "\n",
        "print(nums_tuple.index(2)) # 1\n",
        "print(nums_tuple.index(3)) # 2"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "JbMo-2X-Js_N",
        "outputId": "45b64184-581a-4363-f915-c16c9bcf5eed"
      },
      "execution_count": 19,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "2\n",
            "1\n",
            "2\n",
            "1\n",
            "2\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#문자열에서 사용\n",
        "str = 'kangminheee'\n",
        "print(str.index('k'))  #0\n",
        "print(str.index('h'))  #7\n",
        "print(str.index('i'))  #5\n",
        "#print(str.index('l')) 없는 걸 찾으면 error\n",
        "print(str.index('e'))  #8 -> 여러개면 제일 첫번째것 반환\n",
        "print(str.find('e'))   #8 -> find()는 index()와 같은 기능을 가진 함수\n",
        "print(str.rfind('e'))  #10 -> 여러개중 가장 오른쪽 것 반환\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "gPWSfLsGJtBi",
        "outputId": "a76b6f9c-6938-4437-c99c-a42f626bd054"
      },
      "execution_count": 20,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0\n",
            "7\n",
            "5\n",
            "8\n",
            "8\n",
            "10\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "hz = \"홈짱닷컴 Homzzang.com\"\n",
        "\n",
        "x = hz.rindex(\"Homzzang\")\n",
        "\n",
        "print(x)\n",
        "\n",
        "x = hz.rindex(\"o\", 2)\n",
        "print(x)\n",
        "\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "_Qv9q5iZJtDo",
        "outputId": "02faced2-e1d3-4d3f-b75c-85bcaa8dbd10"
      },
      "execution_count": 21,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "5\n",
            "15\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "text = 'Welcome to Codetorial'\n",
        "\n",
        "pos_Code_last = text.lower().rindex('code')\n",
        "print(pos_Code_last)\n",
        "\n",
        "pos_code_last = text.lower().rindex('code')\n",
        "print(pos_code_last)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "n5KgIGo0J3Cn",
        "outputId": "3fdecf52-1088-47bd-a93b-978d9e8d4af5"
      },
      "execution_count": 23,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "11\n",
            "11\n"
          ]
        }
      ]
    }
  ]
}
