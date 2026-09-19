<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzfk-sivt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="fzfk-sivt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-friends" {...props}></Icon>
