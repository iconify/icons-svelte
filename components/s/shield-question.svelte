<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jase8vblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jase8vblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:shield-question" {...props}></Icon>
