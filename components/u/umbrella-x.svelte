<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3fzftb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3fzftb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:umbrella-x" {...props}></Icon>
