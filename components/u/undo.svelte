<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at8qoi4ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="at8qoi4ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:undo" {...props}></Icon>
