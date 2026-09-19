<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc7t5-bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="lc7t5-bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:wheelchair" {...props}></Icon>
