<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv8cfeb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv8cfeb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tryhackme" {...props}></Icon>
