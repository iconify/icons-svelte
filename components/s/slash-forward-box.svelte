<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxnpktnth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxnpktnth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:slash-forward-box" {...props}></Icon>
