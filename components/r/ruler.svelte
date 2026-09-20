<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwb6_vbxr.css';
import '../../css/z/z5g1e3aps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwb6_vbxr"/><path class="z5g1e3aps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:ruler" {...props}></Icon>
