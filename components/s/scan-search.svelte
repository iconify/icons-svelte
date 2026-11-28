<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpwr8lbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpwr8lbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:scan-search" {...props}></Icon>
