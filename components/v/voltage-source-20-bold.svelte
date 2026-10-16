<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1aumdb7c.css';
import '../../css/a/a8jlsdb4l.css';
import '../../css/m/mj6ibrhop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i1aumdb7c"/><path class="a8jlsdb4l"/><path class="mj6ibrhop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-source-20-bold" {...props}></Icon>
