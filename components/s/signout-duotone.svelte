<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyuumbbis.css';
import '../../css/z/zridksdbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyuumbbis"/><path class="zridksdbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:signout-duotone" {...props}></Icon>
