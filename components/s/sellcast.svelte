<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci0f6_brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ci0f6_brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sellcast" {...props}></Icon>
