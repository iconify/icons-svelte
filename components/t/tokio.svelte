<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc12xobfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc12xobfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tokio" {...props}></Icon>
