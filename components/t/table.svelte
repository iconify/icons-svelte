<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki3501y0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki3501y0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:table" {...props}></Icon>
