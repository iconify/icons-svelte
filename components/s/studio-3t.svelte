<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a16dl8ikz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a16dl8ikz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:studio-3t" {...props}></Icon>
