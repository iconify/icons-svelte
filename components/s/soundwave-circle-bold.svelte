<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt7g0ubvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jt7g0ubvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:soundwave-circle-bold" {...props}></Icon>
