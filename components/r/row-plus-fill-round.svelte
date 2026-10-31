<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u17he8btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u17he8btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:row-plus-fill-round" {...props}></Icon>
