<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa_ewxbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa_ewxbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xendit" {...props}></Icon>
