<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhj1_zgpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uhj1_zgpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:transgender" {...props}></Icon>
