<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dra7irbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dra7irbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:screen-broadcast-solid" {...props}></Icon>
