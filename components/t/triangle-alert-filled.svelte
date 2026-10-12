<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxpnsylsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uxpnsylsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:triangle-alert-filled" {...props}></Icon>
