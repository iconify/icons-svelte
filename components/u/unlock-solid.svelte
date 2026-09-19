<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nds9cwbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nds9cwbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:unlock-solid" {...props}></Icon>
