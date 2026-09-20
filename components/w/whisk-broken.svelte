<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz7vl2bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz7vl2bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:whisk-broken" {...props}></Icon>
