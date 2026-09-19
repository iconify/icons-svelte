<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hicz8ocee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hicz8ocee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:signal-no-01" {...props}></Icon>
