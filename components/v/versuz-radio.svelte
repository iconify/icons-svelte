<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9bfyrst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv9bfyrst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:versuz-radio" {...props}></Icon>
