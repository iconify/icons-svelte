<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eskr5jboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eskr5jboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sync-alt" {...props}></Icon>
