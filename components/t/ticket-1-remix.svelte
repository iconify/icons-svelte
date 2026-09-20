<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpa6e9sza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mpa6e9sza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ticket-1-remix" {...props}></Icon>
