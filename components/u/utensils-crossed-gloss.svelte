<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6lj_ebwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6lj_ebwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:utensils-crossed-gloss" {...props}></Icon>
