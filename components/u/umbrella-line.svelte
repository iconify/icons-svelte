<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt44b3btn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt44b3btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:umbrella-line" {...props}></Icon>
