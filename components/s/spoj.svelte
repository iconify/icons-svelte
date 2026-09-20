<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbbo_dbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbbo_dbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:spoj" {...props}></Icon>
