<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwn-x6e3b.css';
import '../../css/k/k9cm14b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwn-x6e3b"/><path class="k9cm14b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:test-tube-minimalistic-bold" {...props}></Icon>
