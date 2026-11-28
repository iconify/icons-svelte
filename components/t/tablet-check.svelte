<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5wm5qbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5wm5qbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tablet-check" {...props}></Icon>
