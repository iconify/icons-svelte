<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnnz_hrwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1536};
const content = `<path class="rnnz_hrwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:television" {...props}></Icon>
