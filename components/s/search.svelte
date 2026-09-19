<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo3f9221g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo3f9221g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:search" {...props}></Icon>
