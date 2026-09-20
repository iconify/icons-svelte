<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lof-am1yz.css';
import '../../css/p/pky0achnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lof-am1yz"/><path clip-rule="evenodd" class="pky0achnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:winrar-outline" {...props}></Icon>
