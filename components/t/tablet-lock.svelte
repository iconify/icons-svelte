<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yogw2bbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yogw2bbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tablet-lock" {...props}></Icon>
