<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vig41oomx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vig41oomx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:steps-number-solid" {...props}></Icon>
