<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioxp4mbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioxp4mbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:square-arrow-down" {...props}></Icon>
