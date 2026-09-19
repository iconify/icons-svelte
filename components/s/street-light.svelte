<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/x/xgtstcblw.css';
import '../../css/z/zxllwrblm.css';
import '../../css/m/ms-hx8b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="xgtstcblw"/><path class="zxllwrblm"/><path class="ms-hx8b4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:street-light" {...props}></Icon>
