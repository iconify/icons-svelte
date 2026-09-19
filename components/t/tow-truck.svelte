<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nso-06b-q.css';
import '../../css/z/zf0gdub7b.css';
import '../../css/b/bouo_5bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nso-06b-q"/><path class="zf0gdub7b"/><path class="bouo_5bdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tow-truck" {...props}></Icon>
