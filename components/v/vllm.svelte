<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi5j1db3c.css';
import '../../css/p/pgxnyljae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi5j1db3c"/><path class="pgxnyljae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vllm" {...props}></Icon>
