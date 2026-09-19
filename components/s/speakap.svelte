<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kur4tfbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kur4tfbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:speakap" {...props}></Icon>
