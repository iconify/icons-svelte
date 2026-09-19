<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfz-e7d_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="cfz-e7d_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:volume-off" {...props}></Icon>
