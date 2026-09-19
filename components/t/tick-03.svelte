<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng093b3vj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng093b3vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tick-03" {...props}></Icon>
