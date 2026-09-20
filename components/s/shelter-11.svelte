<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke56rmbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ke56rmbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:shelter-11" {...props}></Icon>
