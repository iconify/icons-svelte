<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8fmazbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8fmazbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:window-line" {...props}></Icon>
