<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tywfxp2wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tywfxp2wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-surprised-solid" {...props}></Icon>
