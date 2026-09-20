<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6-qkpbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s6-qkpbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:shield-1-flat" {...props}></Icon>
