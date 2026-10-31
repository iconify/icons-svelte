<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/demh73b4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="demh73b4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:zoom-out-gloss" {...props}></Icon>
