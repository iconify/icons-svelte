<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5i0m2t_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b5i0m2t_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:threeraysbelow" {...props}></Icon>
