<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6_shdyey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f6_shdyey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ticket-1-solid" {...props}></Icon>
