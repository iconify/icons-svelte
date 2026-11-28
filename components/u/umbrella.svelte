<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv94c6bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv94c6bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:umbrella" {...props}></Icon>
