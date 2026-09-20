<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk8sppb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tk8sppb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:toilet-man-woman-1-remix" {...props}></Icon>
