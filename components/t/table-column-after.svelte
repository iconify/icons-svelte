<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-zhgxbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="s-zhgxbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:table-column-after" {...props}></Icon>
