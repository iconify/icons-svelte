<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0ffv4kgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="j0ffv4kgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:star-empty" {...props}></Icon>
