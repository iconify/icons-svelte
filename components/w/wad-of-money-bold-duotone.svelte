<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5lttmq7g.css';
import '../../css/n/n6jo5gq3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5lttmq7g"/><path class="n6jo5gq3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wad-of-money-bold-duotone" {...props}></Icon>
