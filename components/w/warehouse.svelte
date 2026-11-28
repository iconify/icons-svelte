<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgdzr_klv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgdzr_klv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:warehouse" {...props}></Icon>
