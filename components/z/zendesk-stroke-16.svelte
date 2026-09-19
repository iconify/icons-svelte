<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvk-mpx8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vvk-mpx8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:zendesk-stroke-16" {...props}></Icon>
