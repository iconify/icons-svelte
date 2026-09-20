<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thi1-bctc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="thi1-bctc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:ruler" {...props}></Icon>
