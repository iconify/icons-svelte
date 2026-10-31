<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j92as5bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j92as5bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-close-fill-round" {...props}></Icon>
