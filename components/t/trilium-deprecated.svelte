<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiswrynqd.css';
import '../../css/m/mnxwnsb-q.css';
import '../../css/r/rce-0p68g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tiswrynqd"/><path class="mnxwnsb-q"/><path class="rce-0p68g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trilium-deprecated" {...props}></Icon>
