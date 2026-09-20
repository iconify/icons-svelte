<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayka6ccdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayka6ccdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:three-rows" {...props}></Icon>
