<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu3kl0h8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu3kl0h8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:user" {...props}></Icon>
