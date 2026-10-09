<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il0bcibcq.css';
import '../../css/z/z8-myrbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="il0bcibcq"/><path class="z8-myrbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:temperature-20" {...props}></Icon>
