<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb3xjqbob.css';
import '../../css/y/yennaobau.css';
import '../../css/r/rk2pofpji.css';
import '../../css/u/ur75d4b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hb3xjqbob"/><path class="yennaobau"/><path class="rk2pofpji"/><path class="ur75d4b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-panel-sun-48" {...props}></Icon>
