<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb3-mo94e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb3-mo94e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:trending-down" {...props}></Icon>
