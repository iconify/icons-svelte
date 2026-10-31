<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi6snsb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi6snsb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:signal-gloss" {...props}></Icon>
