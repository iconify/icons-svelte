<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn-2ng51c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nn-2ng51c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:text-document" {...props}></Icon>
