<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8kir8brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8kir8brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-big-code-filled" {...props}></Icon>
