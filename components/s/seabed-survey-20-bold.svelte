<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2cwbgbog.css';
import '../../css/m/mqzn7v0fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i2cwbgbog"/><path class="mqzn7v0fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seabed-survey-20-bold" {...props}></Icon>
