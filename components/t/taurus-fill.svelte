<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqo7qpbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqo7qpbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:taurus-fill" {...props}></Icon>
