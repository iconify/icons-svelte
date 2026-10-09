<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3ezex0cb.css';
import '../../css/h/hldpdtbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t3ezex0cb"/><path class="hldpdtbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:upload-cloud-20-bold" {...props}></Icon>
