<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3schulug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r3schulug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:vim-outline" {...props}></Icon>
