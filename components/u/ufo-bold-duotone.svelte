<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgv6vob-r.css';
import '../../css/d/dr-zygb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgv6vob-r"/><path class="dr-zygb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ufo-bold-duotone" {...props}></Icon>
