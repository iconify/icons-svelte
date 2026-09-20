<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0l0iie8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e0l0iie8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:subtract-1-solid" {...props}></Icon>
