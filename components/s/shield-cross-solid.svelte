<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xji6mnbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xji6mnbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shield-cross-solid" {...props}></Icon>
