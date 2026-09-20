<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrh7y0bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="jrh7y0bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:strikethrough-1" {...props}></Icon>
