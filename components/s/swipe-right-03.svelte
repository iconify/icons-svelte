<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfzg1kbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfzg1kbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-right-03" {...props}></Icon>
