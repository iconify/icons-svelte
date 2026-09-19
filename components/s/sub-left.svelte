<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc-u6umse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc-u6umse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:sub-left" {...props}></Icon>
