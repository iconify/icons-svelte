<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh4-i6bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh4-i6bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:scrimba" {...props}></Icon>
