<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwo_g8yno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iwo_g8yno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:transfer-truck-time-remix" {...props}></Icon>
