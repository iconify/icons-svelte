<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha9sq_r2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ha9sq_r2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:thumbs-up" {...props}></Icon>
