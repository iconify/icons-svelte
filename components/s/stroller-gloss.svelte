<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5x_c4b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5x_c4b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:stroller-gloss" {...props}></Icon>
