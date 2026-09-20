<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umel8k68n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umel8k68n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:smiley-neutral-24" {...props}></Icon>
