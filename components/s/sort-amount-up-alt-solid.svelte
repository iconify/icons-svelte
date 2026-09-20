<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny1r5jixv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ny1r5jixv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sort-amount-up-alt-solid" {...props}></Icon>
