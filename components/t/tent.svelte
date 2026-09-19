<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-8x6fiyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="s-8x6fiyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:tent" {...props}></Icon>
