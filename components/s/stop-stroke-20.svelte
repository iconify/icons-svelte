<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do-kjs8oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="do-kjs8oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:stop-stroke-20" {...props}></Icon>
