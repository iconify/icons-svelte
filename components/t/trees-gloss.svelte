<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz_d23t2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz_d23t2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trees-gloss" {...props}></Icon>
