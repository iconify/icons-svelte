<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd7zsrb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd7zsrb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tv-play" {...props}></Icon>
