<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt8u4qbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vt8u4qbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:superhero-alt" {...props}></Icon>
