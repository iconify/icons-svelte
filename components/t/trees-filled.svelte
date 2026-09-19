<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1otxkt3x.css';
import '../../css/y/yic1v-1qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1otxkt3x"/><path class="yic1v-1qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:trees-filled" {...props}></Icon>
