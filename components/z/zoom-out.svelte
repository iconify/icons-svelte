<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjo09pblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjo09pblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:zoom-out" {...props}></Icon>
