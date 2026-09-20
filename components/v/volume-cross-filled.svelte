<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opoym8b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opoym8b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:volume-cross-filled" {...props}></Icon>
