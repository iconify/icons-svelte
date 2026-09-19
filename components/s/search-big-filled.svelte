<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbv6qjqqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbv6qjqqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-big-filled" {...props}></Icon>
