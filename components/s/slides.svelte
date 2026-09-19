<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwdo78b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwdo78b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:slides" {...props}></Icon>
