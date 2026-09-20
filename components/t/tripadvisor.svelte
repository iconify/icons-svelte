<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maw9n7bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="maw9n7bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tripadvisor" {...props}></Icon>
