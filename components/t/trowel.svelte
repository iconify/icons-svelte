<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk3tbmr1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="sk3tbmr1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:trowel" {...props}></Icon>
