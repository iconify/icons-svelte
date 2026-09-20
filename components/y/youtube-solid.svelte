<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx3z-nbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lx3z-nbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:youtube-solid" {...props}></Icon>
