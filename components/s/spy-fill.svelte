<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u86-pacbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u86-pacbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:spy-fill" {...props}></Icon>
