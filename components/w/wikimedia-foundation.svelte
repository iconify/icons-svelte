<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2l8rhbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2l8rhbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wikimedia-foundation" {...props}></Icon>
