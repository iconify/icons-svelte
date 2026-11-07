<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/g/gy84gfb-f.css';
import '../../css/s/sqo895pky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="gy84gfb-f"/><path class="sqo895pky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:send-square-bold-duotone" {...props}></Icon>
