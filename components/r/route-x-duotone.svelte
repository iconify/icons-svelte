<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axvkndb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axvkndb_w primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:route-x-duotone" {...props}></Icon>
