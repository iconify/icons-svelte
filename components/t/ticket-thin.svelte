<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt33bw9wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt33bw9wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:ticket-thin" {...props}></Icon>
