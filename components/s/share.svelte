<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9u0zxhna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y9u0zxhna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:share" {...props}></Icon>
