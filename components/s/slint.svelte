<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/senz0-dsw.css';
import '../../css/b/bwz9z8l8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="senz0-dsw"/><path class="bwz9z8l8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:slint" {...props}></Icon>
