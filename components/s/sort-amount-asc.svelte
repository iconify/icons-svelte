<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idvppfb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1760,"height":1792};
const content = `<path class="idvppfb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:sort-amount-asc" {...props}></Icon>
