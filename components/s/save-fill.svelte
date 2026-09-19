<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrjuh8bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mrjuh8bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:save-fill" {...props}></Icon>
