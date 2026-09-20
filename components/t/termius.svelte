<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p11hu73fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p11hu73fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:termius" {...props}></Icon>
