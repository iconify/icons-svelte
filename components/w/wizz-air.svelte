<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0kw2xsjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0kw2xsjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wizz-air" {...props}></Icon>
