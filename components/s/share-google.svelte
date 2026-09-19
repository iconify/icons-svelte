<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp5sfuo3e.css';
import '../../css/q/qcv-ztbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="jp5sfuo3e"/><path class="qcv-ztbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:share-google" {...props}></Icon>
