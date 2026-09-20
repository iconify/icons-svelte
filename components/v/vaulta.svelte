<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvr3so9tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvr3so9tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vaulta" {...props}></Icon>
