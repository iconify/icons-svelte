<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df934cbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="df934cbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:water-11" {...props}></Icon>
