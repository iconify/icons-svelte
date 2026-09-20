<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1jvxkb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1jvxkb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:zootool-logo" {...props}></Icon>
