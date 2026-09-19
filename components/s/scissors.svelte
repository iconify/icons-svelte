<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zomq738mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zomq738mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:scissors" {...props}></Icon>
