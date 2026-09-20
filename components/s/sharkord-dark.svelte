<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shw5dwbgv.css';
import '../../css/u/u9zmojb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="shw5dwbgv"/><path class="u9zmojb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sharkord-dark" {...props}></Icon>
