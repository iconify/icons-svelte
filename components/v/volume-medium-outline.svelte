<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8unnac5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i8unnac5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:volume-medium-outline" {...props}></Icon>
