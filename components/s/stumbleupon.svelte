<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3_4cdcfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="a3_4cdcfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:stumbleupon" {...props}></Icon>
