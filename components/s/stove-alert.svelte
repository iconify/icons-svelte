<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjtvx7-gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjtvx7-gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:stove-alert" {...props}></Icon>
