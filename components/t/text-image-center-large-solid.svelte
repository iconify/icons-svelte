<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj966c6gj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pj966c6gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:text-image-center-large-solid" {...props}></Icon>
