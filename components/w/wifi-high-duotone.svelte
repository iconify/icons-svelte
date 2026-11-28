<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6zafjb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6zafjb8i primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wifi-high-duotone" {...props}></Icon>
