<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skpsf7bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skpsf7bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:scissors-gloss" {...props}></Icon>
