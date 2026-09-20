<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cec67vb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cec67vb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-alphabetical-ascending-variant" {...props}></Icon>
