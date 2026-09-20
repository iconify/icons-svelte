<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw0twcb-j.css';
import '../../css/a/a8xdzwblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw0twcb-j"/><path class="a8xdzwblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:volume-control-up-3-bold" {...props}></Icon>
