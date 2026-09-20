<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfpc-lb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="nfpc-lb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:screen-alt-2-solid" {...props}></Icon>
