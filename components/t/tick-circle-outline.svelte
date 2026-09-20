<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ext-fqzpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ext-fqzpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:tick-circle-outline" {...props}></Icon>
