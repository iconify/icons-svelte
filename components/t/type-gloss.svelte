<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/domj21oca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="domj21oca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:type-gloss" {...props}></Icon>
