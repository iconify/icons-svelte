<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4ql1vbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x4ql1vbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:search-visual-solid" {...props}></Icon>
