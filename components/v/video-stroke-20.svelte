<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akn59mbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="akn59mbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:video-stroke-20" {...props}></Icon>
