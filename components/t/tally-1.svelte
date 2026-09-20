<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/barz0mwnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="barz0mwnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:tally-1" {...props}></Icon>
