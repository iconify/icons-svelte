<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4va6x1fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4va6x1fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:smoke-free" {...props}></Icon>
