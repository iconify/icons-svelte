<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8zu5fzsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r8zu5fzsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:vimeo-with-circle" {...props}></Icon>
