<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxxbmibop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":184,"height":384};
const content = `<path class="oxxbmibop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:zero" {...props}></Icon>
