<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjsuzrt7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vjsuzrt7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:tablet-fill" {...props}></Icon>
