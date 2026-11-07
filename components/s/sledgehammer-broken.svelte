<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atj5g8h1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atj5g8h1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sledgehammer-broken" {...props}></Icon>
