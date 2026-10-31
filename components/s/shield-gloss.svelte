<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puds2jauh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puds2jauh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-gloss" {...props}></Icon>
