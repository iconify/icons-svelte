<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onvd9_bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="onvd9_bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:unlink" {...props}></Icon>
