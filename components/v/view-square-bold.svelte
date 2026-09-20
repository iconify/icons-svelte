<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3fa7zbhj.css';
import '../../css/p/p5t4w3b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3fa7zbhj"/><path class="p5t4w3b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:view-square-bold" {...props}></Icon>
