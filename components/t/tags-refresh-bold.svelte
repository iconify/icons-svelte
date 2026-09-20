<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5fyvxggv.css';
import '../../css/k/k3qeubcag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5fyvxggv"/><path class="k3qeubcag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:tags-refresh-bold" {...props}></Icon>
