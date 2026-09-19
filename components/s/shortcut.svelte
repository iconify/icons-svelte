<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz17t_8qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="tz17t_8qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:shortcut" {...props}></Icon>
