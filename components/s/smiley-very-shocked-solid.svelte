<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxw-lso_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mxw-lso_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-very-shocked-solid" {...props}></Icon>
