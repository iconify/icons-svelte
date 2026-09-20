<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuarl10qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuarl10qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:smart" {...props}></Icon>
