<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7g2i_2hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v7g2i_2hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:wrap-text" {...props}></Icon>
