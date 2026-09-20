<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nss6r-b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nss6r-b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:woman" {...props}></Icon>
