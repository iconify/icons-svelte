<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb023bcmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb023bcmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sidebar-fold-line" {...props}></Icon>
