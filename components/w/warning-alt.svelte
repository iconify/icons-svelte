<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tetntvipe.css';
import '../../css/w/wczsurb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tetntvipe"/><path class="wczsurb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning-alt" {...props}></Icon>
