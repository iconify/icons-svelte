<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdt1a3-6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wdt1a3-6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:visible-solid" {...props}></Icon>
