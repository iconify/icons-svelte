<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtjxqnmmf.css';
import '../../css/f/f2ws4q-cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gtjxqnmmf"/><path class="f2ws4q-cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:switchgear-20" {...props}></Icon>
