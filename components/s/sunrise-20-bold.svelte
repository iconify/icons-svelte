<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fulicxqoo.css';
import '../../css/s/syle989sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fulicxqoo"/><path class="syle989sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sunrise-20-bold" {...props}></Icon>
