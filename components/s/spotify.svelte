<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-b6ff7_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-b6ff7_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:spotify" {...props}></Icon>
