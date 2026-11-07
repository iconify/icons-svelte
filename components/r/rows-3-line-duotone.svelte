<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f_e3mnbwd.css';
import '../../css/b/b8504g80a.css';
import '../../css/c/cex3mhxbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f_e3mnbwd"/><path class="b8504g80a"/><path class="cex3mhxbq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-3-line-duotone" {...props}></Icon>
