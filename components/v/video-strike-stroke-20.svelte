<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln-9uj60l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ln-9uj60l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:video-strike-stroke-20" {...props}></Icon>
