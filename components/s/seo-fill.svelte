<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-o8ulbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-o8ulbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:seo-fill" {...props}></Icon>
