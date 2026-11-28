<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfl8bdbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfl8bdbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sd-card-x" {...props}></Icon>
