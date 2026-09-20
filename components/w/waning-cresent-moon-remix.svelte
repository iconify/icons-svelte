<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgyzkzbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tgyzkzbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:waning-cresent-moon-remix" {...props}></Icon>
