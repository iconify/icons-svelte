<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6b-uub8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6b-uub8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tinygrad" {...props}></Icon>
