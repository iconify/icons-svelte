<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpqjribuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpqjribuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:sleep-off" {...props}></Icon>
