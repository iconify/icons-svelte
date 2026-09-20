<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6yhmq1dy.css';
import '../../css/b/bc3db-fby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6yhmq1dy"/><path class="bc3db-fby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-cog-duotone" {...props}></Icon>
