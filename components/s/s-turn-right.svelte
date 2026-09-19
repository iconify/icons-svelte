<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/v/v2d09-zvp.css';
import '../../css/w/w-mxnd3nu.css';
import '../../css/a/as11npkhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="v2d09-zvp"/><path class="w-mxnd3nu"/><circle transform="rotate(-180 37.176 10)" class="as11npkhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:s-turn-right" {...props}></Icon>
