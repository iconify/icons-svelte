<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzo-r3c9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzo-r3c9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:volume-down" {...props}></Icon>
