<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnp1ws47m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dnp1ws47m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:zodiac-8-solid" {...props}></Icon>
