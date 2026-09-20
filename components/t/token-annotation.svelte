<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu9kdvbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nu9kdvbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-annotation" {...props}></Icon>
