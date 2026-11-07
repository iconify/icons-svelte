<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9y477w0i.css';
import '../../css/c/cj0d3vbqu.css';
import '../../css/d/dvn5fybze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="n9y477w0i"/><path class="cj0d3vbqu"/><path class="dvn5fybze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-check-bold-duotone" {...props}></Icon>
