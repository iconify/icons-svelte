<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6f34bfwl.css';
import '../../css/p/pgrv-bcfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6f34bfwl"/><path clip-rule="evenodd" class="pgrv-bcfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:unlock-outline" {...props}></Icon>
