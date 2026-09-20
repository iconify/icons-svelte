<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvne9nv5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvne9nv5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tools-line" {...props}></Icon>
