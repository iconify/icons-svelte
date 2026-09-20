<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4o7uwb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4o7uwb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:scaling-left" {...props}></Icon>
