<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxq6cbcbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxq6cbcbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sim-card-lock" {...props}></Icon>
