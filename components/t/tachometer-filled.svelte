<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6ghvs01x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6ghvs01x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tachometer-filled" {...props}></Icon>
