<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqm9qnbgq.css';
import '../../css/u/u5ujo24lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wqm9qnbgq"/><path class="u5ujo24lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:text-background-color-20" {...props}></Icon>
