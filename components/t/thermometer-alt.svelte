<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roqo4bagl.css';
import '../../css/d/d9--onbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roqo4bagl"/><path class="d9--onbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:thermometer-alt" {...props}></Icon>
