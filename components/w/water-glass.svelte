<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqa84pstj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqa84pstj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:water-glass" {...props}></Icon>
