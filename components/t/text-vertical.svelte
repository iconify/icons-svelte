<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8l9ejb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="m8l9ejb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:text-vertical" {...props}></Icon>
