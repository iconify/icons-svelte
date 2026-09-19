<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stvv9dr8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stvv9dr8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:send-horizontal" {...props}></Icon>
