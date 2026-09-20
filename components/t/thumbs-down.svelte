<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmdv5sb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmdv5sb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:thumbs-down" {...props}></Icon>
