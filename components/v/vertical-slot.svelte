<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qllzi2dkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qllzi2dkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vertical-slot" {...props}></Icon>
