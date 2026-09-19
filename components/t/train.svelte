<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3ze4ub9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3ze4ub9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:train" {...props}></Icon>
