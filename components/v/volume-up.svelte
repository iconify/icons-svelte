<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbzqi4cyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":24};
const content = `<path class="fbzqi4cyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:volume-up" {...props}></Icon>
