<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abq2ryzfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abq2ryzfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:undo" {...props}></Icon>
