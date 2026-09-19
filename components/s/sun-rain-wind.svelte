<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj0xs51-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj0xs51-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sun-rain-wind" {...props}></Icon>
