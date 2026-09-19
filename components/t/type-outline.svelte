<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzcw81byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzcw81byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:type-outline" {...props}></Icon>
