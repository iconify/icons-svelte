<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iedm-lb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":115,"height":26};
const content = `<path class="iedm-lb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-help-center-26" {...props}></Icon>
