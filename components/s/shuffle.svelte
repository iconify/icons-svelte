<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9vojfbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="o9vojfbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:shuffle" {...props}></Icon>
