<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhr3rnc_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhr3rnc_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:suitcase-3-line" {...props}></Icon>
