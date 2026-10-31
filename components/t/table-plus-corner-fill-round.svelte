<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fns7kab-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fns7kab-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:table-plus-corner-fill-round" {...props}></Icon>
