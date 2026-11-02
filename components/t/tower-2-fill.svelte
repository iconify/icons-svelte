<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw08exeux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw08exeux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tower-2-fill" {...props}></Icon>
