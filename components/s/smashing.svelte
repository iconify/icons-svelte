<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg-90vbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cg-90vbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:smashing" {...props}></Icon>
