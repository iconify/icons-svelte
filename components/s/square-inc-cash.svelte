<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9wqcob7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9wqcob7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:square-inc-cash" {...props}></Icon>
