<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff2rc26gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ff2rc26gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uxwizz-light" {...props}></Icon>
