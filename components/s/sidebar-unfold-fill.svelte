<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr5oj0o0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr5oj0o0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sidebar-unfold-fill" {...props}></Icon>
