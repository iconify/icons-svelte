<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6qs1ir4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6qs1ir4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:trophy" {...props}></Icon>
