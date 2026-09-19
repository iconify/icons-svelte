<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdn_s7btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jdn_s7btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiral-bloom" {...props}></Icon>
