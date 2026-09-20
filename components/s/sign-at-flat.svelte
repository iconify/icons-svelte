<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rve-l_nnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rve-l_nnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:sign-at-flat" {...props}></Icon>
