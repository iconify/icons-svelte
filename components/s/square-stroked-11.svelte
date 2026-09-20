<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etpkxhbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="etpkxhbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:square-stroked-11" {...props}></Icon>
