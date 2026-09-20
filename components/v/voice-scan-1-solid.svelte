<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddnwvge2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ddnwvge2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:voice-scan-1-solid" {...props}></Icon>
