<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri_2t2kgv.css';
import '../../css/w/w9r2jnnqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ri_2t2kgv"/><path class="w9r2jnnqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:twospeechbubbles" {...props}></Icon>
