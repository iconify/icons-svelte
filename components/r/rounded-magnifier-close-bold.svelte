<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq5k-cbtl.css';
import '../../css/u/ux6q9evhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq5k-cbtl"/><path clip-rule="evenodd" class="ux6q9evhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-close-bold" {...props}></Icon>
