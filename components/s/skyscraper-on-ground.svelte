<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwyfjgb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pwyfjgb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:skyscraper-on-ground" {...props}></Icon>
