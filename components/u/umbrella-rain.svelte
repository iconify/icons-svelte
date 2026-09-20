<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5oonfqix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5oonfqix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:umbrella-rain" {...props}></Icon>
