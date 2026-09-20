<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olip4ntqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olip4ntqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tunnel-line" {...props}></Icon>
