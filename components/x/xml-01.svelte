<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-41i3s2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-41i3s2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:xml-01" {...props}></Icon>
