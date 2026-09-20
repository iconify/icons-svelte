<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la86vc54v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="la86vc54v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tinder" {...props}></Icon>
