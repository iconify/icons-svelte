<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_6ffacll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_6ffacll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:subscript" {...props}></Icon>
