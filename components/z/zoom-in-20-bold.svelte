<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj3zoshwv.css';
import '../../css/v/vlib7y67t.css';
import '../../css/d/duqi8c8_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jj3zoshwv"/><path class="vlib7y67t"/><path class="duqi8c8_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:zoom-in-20-bold" {...props}></Icon>
