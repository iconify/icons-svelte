<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbihz6m0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xbihz6m0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:upload-fill-12" {...props}></Icon>
