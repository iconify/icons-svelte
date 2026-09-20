<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynzsieb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynzsieb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:whisk" {...props}></Icon>
