<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq5k-cbtl.css';
import '../../css/o/opdy_4y2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq5k-cbtl"/><path clip-rule="evenodd" class="opdy_4y2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-slash-bold" {...props}></Icon>
