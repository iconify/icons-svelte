<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev-1yjbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev-1yjbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:stmx" {...props}></Icon>
