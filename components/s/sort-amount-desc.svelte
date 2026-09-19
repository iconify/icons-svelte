<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikq9_k5ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1760,"height":1792};
const content = `<path class="ikq9_k5ko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:sort-amount-desc" {...props}></Icon>
