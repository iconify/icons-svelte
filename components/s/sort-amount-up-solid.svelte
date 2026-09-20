<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln6tz6b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ln6tz6b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sort-amount-up-solid" {...props}></Icon>
