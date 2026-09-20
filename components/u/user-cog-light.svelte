<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8oo03bfv.css';
import '../../css/o/o9-v1yxgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8oo03bfv"/><path class="o9-v1yxgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-cog-light" {...props}></Icon>
