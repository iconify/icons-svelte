<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coos0r0bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coos0r0bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:speaker-gloss" {...props}></Icon>
