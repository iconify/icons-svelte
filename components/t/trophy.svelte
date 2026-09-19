<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ievg71uhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ievg71uhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:trophy" {...props}></Icon>
