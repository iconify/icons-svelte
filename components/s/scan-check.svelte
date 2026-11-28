<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-mmkmb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-mmkmb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:scan-check" {...props}></Icon>
