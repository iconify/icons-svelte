<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhgcf8bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bhgcf8bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:rupee-outline" {...props}></Icon>
