<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m464xxf6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="m464xxf6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:steps-number" {...props}></Icon>
