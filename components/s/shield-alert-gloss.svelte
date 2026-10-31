<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r12vz6boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r12vz6boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-alert-gloss" {...props}></Icon>
