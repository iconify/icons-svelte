<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fulicxqoo.css';
import '../../css/e/e8evysbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fulicxqoo"/><path class="e8evysbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sunset-20-bold" {...props}></Icon>
