<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrf6z8bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrf6z8bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tmux" {...props}></Icon>
