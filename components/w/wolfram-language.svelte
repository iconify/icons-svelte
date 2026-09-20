<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgfrr_9ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgfrr_9ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:wolfram-language" {...props}></Icon>
