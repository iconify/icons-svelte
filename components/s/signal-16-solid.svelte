<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mim6rebae.css';
import '../../css/t/tfnvfpbmm.css';
import '../../css/a/at4prjc-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mim6rebae"/><path clip-rule="evenodd" class="tfnvfpbmm"/><path clip-rule="evenodd" class="at4prjc-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:signal-16-solid" {...props}></Icon>
