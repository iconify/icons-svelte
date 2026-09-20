<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi9jj-4wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="oi9jj-4wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:university" {...props}></Icon>
