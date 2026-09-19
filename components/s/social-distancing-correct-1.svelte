<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/x/xr6lt4bch.css';
import '../../css/l/lzmkr4bin.css';
import '../../css/c/c_qsmmbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xr6lt4bch"/><path class="lzmkr4bin"/><path class="c_qsmmbtu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:social-distancing-correct-1" {...props}></Icon>
