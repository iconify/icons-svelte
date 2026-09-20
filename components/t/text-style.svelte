<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm45gt85n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cm45gt85n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:text-style" {...props}></Icon>
