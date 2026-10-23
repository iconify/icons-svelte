<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9sjz1bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9sjz1bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tally-4" {...props}></Icon>
