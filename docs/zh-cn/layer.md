# 布局

## flex布局
> 使用flex布局的时候要加入class `flex`
### 固定尺寸

<table>
    <tr>
        <td width="20%">
            <table>
                <thead>
                    <tr>
                        <th>说明</th>
                        <th>className</th>
                    </tr>
                </thead>
            <tr>
                <td>xs(20%)</td>
                <td>basis-xs</td>
            </tr>
            <tr>
                <td>sm(40%)</td>
                <td>basis-sm</td>
            </tr>
            <tr>
                <td>sub(50%)</td>
                <td>basis-sub</td>
            </tr>
            <tr>
                <td>lg(60%) </td>
                <td>basis-lg</td>
            </tr>
            <tr>
                <td>xl(80%)</td>
                <td>basis-xl</td>
            </tr>
            </table>
        </td>
        <td width="30%" height="100%">
            <img src="https://omycli.github.io/wuc-docs/_image/flex-g.png" alt="固定尺寸" />
        </td>
    </tr>
</table>

### 比例布局

<table>
    <tr>
        <td width="20%">
            <table>
                <thead>
                    <tr>
                        <th>说明</th>
                        <th>className</th>
                    </tr>
                </thead>
            <tr>
                <td>1:1</td>
                <td>flex-sub</td>
            </tr>
            <tr>
                <td>1:2</td>
                <td>flex-twice</td>
            </tr>
            <tr>
                <td>1:3</td>
                <td>flex-treble</td>
            </tr>
            </table>
        </td>
        <td width="30%" height="100%">
            <img src="https://omycli.github.io/wuc-docs/_image/flex-b.png" alt="比例布局" />
        </td>
    </tr>
</table>

### 水平对齐

<table>
    <tr>
        <td width="20%">
            <table>
                <thead>
                    <tr>
                        <th>说明</th>
                        <th>className</th>
                    </tr>
                </thead>
            <tr>
                <td>左对齐</td>
                <td>justify-start</td>
            </tr>
            <tr>
                <td>右对齐</td>
                <td>justify-end</td>
            </tr>
            <tr>
                <td>居中对齐</td>
                <td>justify-center</td>
            </tr>
            <tr>
                <td>两边对齐</td>
                <td>justify-between</td>
            </tr>
            <tr>
                <td>均匀分散对齐</td>
                <td>justify-around</td>
            </tr>
            </table>
        </td>
        <td width="30%" height="100%">
            <img src="https://omycli.github.io/wuc-docs/_image/flex-j.png" alt="比例布局" />
        </td>
    </tr>
</table>

### 垂直对齐

<table>
    <tr>
        <td width="20%">
            <table>
                <thead>
                    <tr>
                        <th>说明</th>
                        <th>className</th>
                    </tr>
                </thead>
            <tr>
                <td>上对齐</td>
                <td>align-start</td>
            </tr>
            <tr>
                <td>下对齐</td>
                <td>align-end</td>
            </tr>
            <tr>
                <td>居中对齐</td>
                <td>align-center</td>
            </tr>
            </table>
        </td>
        <td width="30%" height="100%">
            <img src="https://omycli.github.io/wuc-docs/_image/flex-a.png" alt="比例布局" />
        </td>
    </tr>
</table>

### 垂直布局

<table>
    <tr>
        <td width="20%">
            <table>
                <thead>
                    <tr>
                        <th>说明</th>
                        <th>className</th>
                    </tr>
                </thead>
            <tr>
                <td>垂直布局</td>
                <td>column</td>
            </tr>
            <tr>
                <td>垂直居中布局</td>
                <td>column-center</td>
            </tr>
            <tr>
                <td>垂直两边对齐</td>
                <td>column-between</td>
            </tr>
            <tr>
                <td>垂直分散对齐</td>
                <td>column-around</td>
            </tr>
            </table>
        </td>
        <td width="30%" height="100%">
            <img src="https://omycli.github.io/wuc-docs/_image/column.png" alt="垂直布局" />
        </td>
    </tr>
</table>

### 水平垂直均居中布局

<table>
    <tr>
        <td width="20%">
            <table>
                <thead>
                    <tr>
                        <th>说明</th>
                        <th>className</th>
                    </tr>
                </thead>
            <tr>
                <td>水平垂直均居中布局</td>
                <td>flex-center</td>
            </tr>
            </table>
        </td>
        <td width="30%" height="100%">
            <img src="https://omycli.github.io/wuc-docs/_image/flex-center.png" alt="水平垂直均居中布局" />
        </td>
    </tr>
</table>

## Grid布局

### 等分列

<table>
    <tr>
        <td width="20%">
            <table>
                <thead>
                    <tr>
                        <th>说明</th>
                        <th>className</th>
                    </tr>
                </thead>
            <tr>
                <td>分列数</td>
                <td>col-(Number)</td>
            </tr>
            </table>
        </td>
        <td width="30%" height="100%">
            <img src="https://omycli.github.io/wuc-docs/_image/grid-d.png" alt="等分列" />
        </td>
    </tr>
</table>

### 等高

<table>
    <tr>
        <td width="20%">
            <table>
                <thead>
                    <tr>
                        <th>说明</th>
                        <th>className</th>
                    </tr>
                </thead>
            <tr>
                <td>分列数</td>
                <td>col-(Number)</td>
            </tr>
            <tr>
                <td>等高属性</td>
                <td>grid-square</td>
            </tr>
            </table>
        </td>
        <td width="30%" height="100%">
            <img src="https://omycli.github.io/wuc-docs/_image/grid-h.png" alt="等高" />
        </td>
    </tr>
</table>

## 辅助布局
### 浮动
<table>
    <tr>
        <td width="20%">
            <table>
                <thead>
                    <tr>
                        <th>说明</th>
                        <th>className</th>
                    </tr>
                </thead>
            <tr>
                <td>左浮动</td>
                <td>fl</td>
            </tr>
            <tr>
                <td>右浮动</td>
                <td>fr</td>
            </tr>
            </table>
        </td>
        <td width="30%" height="100%">
            <img src="https://omycli.github.io/wuc-docs/_image/layer-lr.png" alt="浮动" />
        </td>
    </tr>
</table>

### 内外边距
>{size}的尺寸有xs/sm/df/lg/xl

| 说明           | className             |
| -------------- | --------------------- |
| 外边距         | margin-{size}         |
| 内边距         | padding-{size}        |
| 水平方向外边距 | margin-lr-{size}      |
| 水平方向内边距 | padding-lr-{size}     |
| 垂直方向外边距 | margin-tb-{size}      |
| 垂直方向内边距 | padding-tb-{size}     |
| 上外边距       | margin-top-{size}     |
| 上内边距       | padding-top-{size}    |
| 右外边距       | margin-right-{size}   |
| 右内边距       | padding-right-{size}  |
| 下外边距       | margin-bottom-{size}  |
| 下内边距       | padding-bottom-{size} |
| 左外边距       | margin-left-{size}    |
| 左内边距       | padding-left-{size}   |