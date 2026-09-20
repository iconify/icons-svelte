<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl3nhgb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bl3nhgb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wisgate" {...props}></Icon>
