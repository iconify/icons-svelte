<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0tqoiufg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l0tqoiufg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:scroll-handle" {...props}></Icon>
