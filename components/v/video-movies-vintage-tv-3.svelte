<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxs9kibnt.css';
import '../../css/g/gvn1ulafh.css';
import '../../css/q/qcrc8mb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pxs9kibnt"/><path class="gvn1ulafh"/><path class="qcrc8mb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:video-movies-vintage-tv-3" {...props}></Icon>
