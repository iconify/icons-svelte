<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_144vubq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o_144vubq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:tablet" {...props}></Icon>
