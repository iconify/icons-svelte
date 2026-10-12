<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufby36brl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ufby36brl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:x-small-20" {...props}></Icon>
