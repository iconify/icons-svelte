<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_-4ywbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y_-4ywbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:scale" {...props}></Icon>
