<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wakluybgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wakluybgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:rugby-ball" {...props}></Icon>
