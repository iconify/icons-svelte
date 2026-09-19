<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whkglzwwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whkglzwwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sleep-timer" {...props}></Icon>
