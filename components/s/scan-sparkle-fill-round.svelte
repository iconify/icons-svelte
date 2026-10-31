<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5v1dn0pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5v1dn0pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:scan-sparkle-fill-round" {...props}></Icon>
