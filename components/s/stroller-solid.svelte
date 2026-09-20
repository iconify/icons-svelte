<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yamn3ybiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yamn3ybiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:stroller-solid" {...props}></Icon>
