<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_0b-di9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_0b-di9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:underline-line" {...props}></Icon>
