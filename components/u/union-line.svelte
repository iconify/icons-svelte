<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbb_s8hmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbb_s8hmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:union-line" {...props}></Icon>
