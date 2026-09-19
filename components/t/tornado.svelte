<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etsd8jpcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="etsd8jpcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tornado" {...props}></Icon>
