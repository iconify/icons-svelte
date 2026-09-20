<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxbw_dbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lxbw_dbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:yoga-half-moon-pose-1-bold" {...props}></Icon>
