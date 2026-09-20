<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2qy2kb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h2qy2kb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:snow-flake-solid" {...props}></Icon>
