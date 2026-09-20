<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss_jp_aav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ss_jp_aav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:underline-text-1" {...props}></Icon>
