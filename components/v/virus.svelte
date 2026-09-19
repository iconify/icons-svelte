<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz0nizbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz0nizbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:virus" {...props}></Icon>
