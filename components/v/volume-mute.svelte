<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiipszjjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tiipszjjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:volume-mute" {...props}></Icon>
