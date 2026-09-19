<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr7fh5uak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr7fh5uak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:skip-previous" {...props}></Icon>
