<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lizd04bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lizd04bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:save" {...props}></Icon>
