<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn9smw17t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn9smw17t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:search-fill-round" {...props}></Icon>
