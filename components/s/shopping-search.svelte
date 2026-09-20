<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-z_8uu5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-z_8uu5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shopping-search" {...props}></Icon>
