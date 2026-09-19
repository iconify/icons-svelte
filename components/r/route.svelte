<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzr5unb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fzr5unb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:route" {...props}></Icon>
