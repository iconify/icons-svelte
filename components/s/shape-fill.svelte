<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvgb31bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvgb31bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shape-fill" {...props}></Icon>
