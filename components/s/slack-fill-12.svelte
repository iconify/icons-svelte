<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c916p865d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c916p865d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:slack-fill-12" {...props}></Icon>
