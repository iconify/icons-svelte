<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1zh8pbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1zh8pbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:swap-bold" {...props}></Icon>
