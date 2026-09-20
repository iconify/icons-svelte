<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv_otkb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv_otkb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:stellar" {...props}></Icon>
