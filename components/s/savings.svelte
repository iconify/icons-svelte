<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adq8x7bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adq8x7bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:savings" {...props}></Icon>
