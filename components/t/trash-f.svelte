<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4jeqmivt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="u4jeqmivt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:trash-f" {...props}></Icon>
