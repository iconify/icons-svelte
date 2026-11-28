<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quth05bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quth05bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:volume" {...props}></Icon>
