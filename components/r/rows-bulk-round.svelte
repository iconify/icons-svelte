<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga99nhblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga99nhblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rows-bulk-round" {...props}></Icon>
