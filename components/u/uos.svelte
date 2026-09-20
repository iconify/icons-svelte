<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p13004bfj.css';
import '../../css/m/m79egobtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p13004bfj"/><path class="m79egobtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:uos" {...props}></Icon>
