<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0oydobxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<rect class="i0oydobxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:stop-filled" {...props}></Icon>
