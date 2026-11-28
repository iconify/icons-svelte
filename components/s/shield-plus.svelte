<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0rpkn2qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0rpkn2qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:shield-plus" {...props}></Icon>
