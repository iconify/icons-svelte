<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep-jsbg9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep-jsbg9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shield-line" {...props}></Icon>
