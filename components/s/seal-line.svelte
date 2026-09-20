<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg1uq6s2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg1uq6s2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:seal-line" {...props}></Icon>
