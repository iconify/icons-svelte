<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/h/hx-py_msp.css';
import '../../css/i/i7bfnabyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><path class="hx-py_msp"/><path class="i7bfnabyt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:vip-one" {...props}></Icon>
