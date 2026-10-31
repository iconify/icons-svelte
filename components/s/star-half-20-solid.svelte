<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1lgfrm_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d1lgfrm_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:star-half-20-solid" {...props}></Icon>
