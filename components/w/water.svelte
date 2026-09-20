<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1kvfb.css';
import '../../css/s/so-from-22.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1kvfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:water" {...props}></Icon>
