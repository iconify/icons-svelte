<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxg2urbpi.css';
import '../../css/d/d0fagzbxo.css';
import '../../css/s/s3en1kj6e.css';
import '../../css/v/v385kybwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pxg2urbpi"/><path class="d0fagzbxo"/><path class="s3en1kj6e"/><path class="v385kybwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:wolfface" {...props}></Icon>
