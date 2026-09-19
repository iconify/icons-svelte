<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo1rgluil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo1rgluil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-intersect-filled" {...props}></Icon>
