<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/algwq4ehk.css';
import '../../css/l/ll6ph0b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="algwq4ehk"/><path class="ll6ph0b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-plus-20-bold" {...props}></Icon>
