<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_94e1ufu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_94e1ufu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wine" {...props}></Icon>
