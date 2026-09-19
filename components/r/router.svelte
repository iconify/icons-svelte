<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj_y2v3db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pj_y2v3db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:router" {...props}></Icon>
