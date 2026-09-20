<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp238ub8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp238ub8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stairs" {...props}></Icon>
