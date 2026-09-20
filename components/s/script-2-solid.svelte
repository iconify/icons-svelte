<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfcsk6m0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vfcsk6m0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:script-2-solid" {...props}></Icon>
