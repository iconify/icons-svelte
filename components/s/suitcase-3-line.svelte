<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2c3ygb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2c3ygb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:suitcase-3-line" {...props}></Icon>
