<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0qr93bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0qr93bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:volume-low-line" {...props}></Icon>
