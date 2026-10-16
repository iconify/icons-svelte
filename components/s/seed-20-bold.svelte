<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs1cxybvq.css';
import '../../css/v/v692yrxpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gs1cxybvq"/><path class="v692yrxpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seed-20-bold" {...props}></Icon>
