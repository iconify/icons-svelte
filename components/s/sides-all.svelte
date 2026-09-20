<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flz90fblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="flz90fblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:sides-all" {...props}></Icon>
