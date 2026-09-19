<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px64f9bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="px64f9bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:text" {...props}></Icon>
