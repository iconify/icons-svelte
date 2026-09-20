<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk9mervdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dk9mervdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:toilet-sign-man-flat" {...props}></Icon>
