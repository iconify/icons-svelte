<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4j9ipb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4j9ipb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-bag-1-fill" {...props}></Icon>
