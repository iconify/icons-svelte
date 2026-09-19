<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoskosbxd.css';
import '../../css/j/j1t29sstw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoskosbxd"/><path class="j1t29sstw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:scale-filled" {...props}></Icon>
