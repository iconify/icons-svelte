<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jidg0csbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jidg0csbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tryhackme" {...props}></Icon>
