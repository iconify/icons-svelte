<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u12ihswbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u12ihswbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:volcano" {...props}></Icon>
