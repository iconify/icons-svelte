<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvakp6a-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvakp6a-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wind" {...props}></Icon>
