<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yce_ecd9i.css';
import '../../css/d/dasmli_2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yce_ecd9i"/><circle class="dasmli_2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:tag-ltr" {...props}></Icon>
