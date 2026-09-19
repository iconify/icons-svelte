<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfzbl7pcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfzbl7pcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tool-filled" {...props}></Icon>
