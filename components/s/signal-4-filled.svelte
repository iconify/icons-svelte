<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1zvigbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1zvigbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:signal-4-filled" {...props}></Icon>
