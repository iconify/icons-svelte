<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn64xzbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn64xzbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:trunkrs" {...props}></Icon>
