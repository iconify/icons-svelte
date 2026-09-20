<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbk3j_dhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pbk3j_dhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:watch-circle-time-remix" {...props}></Icon>
