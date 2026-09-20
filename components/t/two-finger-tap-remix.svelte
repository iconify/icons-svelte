<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfpa6p97h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rfpa6p97h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:two-finger-tap-remix" {...props}></Icon>
