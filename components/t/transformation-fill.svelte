<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1h7f4f6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1h7f4f6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:transformation-fill" {...props}></Icon>
