<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4r_v4pue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k4r_v4pue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:upload-circle-solid" {...props}></Icon>
