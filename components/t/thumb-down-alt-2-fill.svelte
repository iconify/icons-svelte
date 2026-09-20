<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1n2fmc-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1n2fmc-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:thumb-down-alt-2-fill" {...props}></Icon>
