<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl-abrbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="bl-abrbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-binary" {...props}></Icon>
