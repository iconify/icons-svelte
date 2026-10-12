<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncd4tklcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ncd4tklcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:table-stroke-20" {...props}></Icon>
