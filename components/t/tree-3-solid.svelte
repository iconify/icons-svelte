<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egwo19joz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="egwo19joz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tree-3-solid" {...props}></Icon>
