<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3gahbc6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3gahbc6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:text-align-center" {...props}></Icon>
