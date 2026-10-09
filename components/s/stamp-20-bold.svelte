<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he4rpzjtd.css';
import '../../css/c/cv0y15bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="he4rpzjtd"/><path class="cv0y15bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stamp-20-bold" {...props}></Icon>
