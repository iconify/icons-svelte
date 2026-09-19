<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-e-epbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p-e-epbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:twitter" {...props}></Icon>
