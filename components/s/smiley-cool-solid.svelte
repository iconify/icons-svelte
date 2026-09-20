<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5bpuob-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v5bpuob-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-cool-solid" {...props}></Icon>
