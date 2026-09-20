<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o155z10jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="o155z10jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:sides-axial" {...props}></Icon>
