<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpqhu_r9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpqhu_r9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unlock-24" {...props}></Icon>
