<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unru5tbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="unru5tbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tipi-campsite-with-peso" {...props}></Icon>
