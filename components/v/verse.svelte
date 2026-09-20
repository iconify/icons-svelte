<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6mk2emto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p6mk2emto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:verse" {...props}></Icon>
