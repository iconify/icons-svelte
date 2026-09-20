<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwtctub0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mwtctub0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:zodiac-5-solid" {...props}></Icon>
