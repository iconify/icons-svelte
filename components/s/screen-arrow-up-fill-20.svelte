<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu5xhwzcj.css';
import '../../css/y/ywttjwgha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xu5xhwzcj"/><path class="ywttjwgha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:screen-arrow-up-fill-20" {...props}></Icon>
