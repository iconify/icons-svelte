<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4fde2bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4fde2bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:timer-off" {...props}></Icon>
