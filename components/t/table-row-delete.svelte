<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plv78-b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="plv78-b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:table-row-delete" {...props}></Icon>
