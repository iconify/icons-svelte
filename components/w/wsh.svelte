<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gezj21rlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gezj21rlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:wsh" {...props}></Icon>
