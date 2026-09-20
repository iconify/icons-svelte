<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnu7rbbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lnu7rbbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:text-document-outline" {...props}></Icon>
