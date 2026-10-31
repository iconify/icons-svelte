<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/metc_zb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="metc_zb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:thandai-gloss" {...props}></Icon>
