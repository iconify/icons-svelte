<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb3o8uw0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jb3o8uw0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-fall-2-outline" {...props}></Icon>
