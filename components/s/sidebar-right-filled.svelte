<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0ac-ybds.css';
import '../../css/b/b6dzwabah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0ac-ybds"/><path class="b6dzwabah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sidebar-right-filled" {...props}></Icon>
