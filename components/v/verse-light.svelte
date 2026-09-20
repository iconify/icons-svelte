<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0a0lpu5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l0a0lpu5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:verse-light" {...props}></Icon>
