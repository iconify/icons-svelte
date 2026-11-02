<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv5xazb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv5xazb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sparkles-fill" {...props}></Icon>
