<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkrzjhblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kkrzjhblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:wordpress-simple" {...props}></Icon>
