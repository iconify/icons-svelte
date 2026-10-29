<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qru5rt3-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qru5rt3-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:x-circle-solid" {...props}></Icon>
