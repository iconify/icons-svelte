<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6j569bdk.css';
import '../../css/l/l9hde_zgu.css';
import '../../css/b/bvzc07axr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6j569bdk"/><path class="l9hde_zgu"/><path class="bvzc07axr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:routing-bold-duotone" {...props}></Icon>
