<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bp8o4e48l.css';
import '../../css/a/aimb84bag.css';
import '../../css/p/pkzm03h6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bp8o4e48l"/><path class="aimb84bag"/><path class="pkzm03h6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:wifi-signal-2" {...props}></Icon>
