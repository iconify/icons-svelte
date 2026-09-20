<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuc8ibcpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vuc8ibcpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:text" {...props}></Icon>
