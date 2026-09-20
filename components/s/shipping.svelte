<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ous84lbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="ous84lbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:shipping" {...props}></Icon>
