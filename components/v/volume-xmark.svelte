<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrr9o3jlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrr9o3jlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:volume-xmark" {...props}></Icon>
