<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul2plrb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="ul2plrb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:upload" {...props}></Icon>
