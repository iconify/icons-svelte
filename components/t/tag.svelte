<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr-36j6gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr-36j6gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tag" {...props}></Icon>
