<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs6k2uf_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs6k2uf_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:tag" {...props}></Icon>
