<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kimoq7uac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="kimoq7uac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:verticalborder" {...props}></Icon>
