<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g95e799uz.css';
import '../../css/v/vpo1j0hds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g95e799uz"/><path clip-rule="evenodd" class="vpo1j0hds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:wallet-outline" {...props}></Icon>
