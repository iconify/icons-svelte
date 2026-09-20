<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrh_nu7ig.css';
import '../../css/l/lq82xlboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrh_nu7ig"/><path clip-rule="evenodd" class="lq82xlboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-search-fill" {...props}></Icon>
