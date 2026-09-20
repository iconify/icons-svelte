<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihpe0-b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ihpe0-b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shipping-truck-solid" {...props}></Icon>
