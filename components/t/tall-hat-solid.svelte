<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq1prjqym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vq1prjqym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tall-hat-solid" {...props}></Icon>
