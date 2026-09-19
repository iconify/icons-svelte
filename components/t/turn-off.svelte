<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj10p5rzw.css';
import '../../css/w/wuaul2ctt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lj10p5rzw"/><path class="wuaul2ctt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:turn-off" {...props}></Icon>
