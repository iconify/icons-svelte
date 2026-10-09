<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmaryiywy.css';
import '../../css/y/ytqlk8bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wmaryiywy"/><path class="ytqlk8bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:traffic-light-20" {...props}></Icon>
