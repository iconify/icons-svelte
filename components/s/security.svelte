<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q45cfb.css';
import '../../css/s/so-from-60.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q45cfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:security" {...props}></Icon>
