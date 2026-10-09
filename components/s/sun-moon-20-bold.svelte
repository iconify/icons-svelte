<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv99k2h7c.css';
import '../../css/v/vz-j8jb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cv99k2h7c"/><path class="vz-j8jb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-moon-20-bold" {...props}></Icon>
