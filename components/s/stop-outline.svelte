<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o07e7hgim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o07e7hgim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:stop-outline" {...props}></Icon>
