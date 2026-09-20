<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u72l21blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="u72l21blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:square-root" {...props}></Icon>
