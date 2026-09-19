<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg2jj14us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wg2jj14us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sequential-palette" {...props}></Icon>
