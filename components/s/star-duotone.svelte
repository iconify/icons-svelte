<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgffjjjky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgffjjjky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:star-duotone" {...props}></Icon>
