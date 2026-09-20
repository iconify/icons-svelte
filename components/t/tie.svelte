<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c422gb8zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c422gb8zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:tie" {...props}></Icon>
