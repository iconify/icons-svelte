<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcpscr_4z.css';
import '../../css/b/b6dzwabah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcpscr_4z"/><path class="b6dzwabah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sidebar-right" {...props}></Icon>
