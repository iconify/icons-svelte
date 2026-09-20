<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcx89nbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rcx89nbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:turnkey-linux-dark" {...props}></Icon>
