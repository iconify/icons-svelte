<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn0rqwsyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn0rqwsyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vest-line" {...props}></Icon>
