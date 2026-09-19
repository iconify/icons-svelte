<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if3aotbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="if3aotbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:themeisle" {...props}></Icon>
