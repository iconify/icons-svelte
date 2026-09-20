<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4wjecb2i.css';
import '../../css/i/ipe7-acuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4wjecb2i"/><path class="ipe7-acuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:treasure-chest-bold" {...props}></Icon>
