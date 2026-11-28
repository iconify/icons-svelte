<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/go3vulb-s.css';
import '../../css/g/gy5vykbhv.css';
import '../../css/j/j6o9z6big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="go3vulb-s"/><path class="gy5vykbhv"/><path class="j6o9z6big"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:signal-medium" {...props}></Icon>
