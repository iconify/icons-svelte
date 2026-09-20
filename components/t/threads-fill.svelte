<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a56g3rbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a56g3rbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:threads-fill" {...props}></Icon>
