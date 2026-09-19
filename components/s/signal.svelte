<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8h4sab-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n8h4sab-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:signal" {...props}></Icon>
