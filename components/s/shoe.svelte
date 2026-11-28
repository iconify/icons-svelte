<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqroa213o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqroa213o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:shoe" {...props}></Icon>
