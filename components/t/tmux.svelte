<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw7a82mon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xw7a82mon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:tmux" {...props}></Icon>
