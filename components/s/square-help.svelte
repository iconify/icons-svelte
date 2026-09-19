<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psrz9t_gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psrz9t_gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:square-help" {...props}></Icon>
