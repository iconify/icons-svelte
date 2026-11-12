<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8nktzdut.css';
import '../../css/l/lcji6ciap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="f8nktzdut"/><path class="lcji6ciap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yubal-dark" {...props}></Icon>
