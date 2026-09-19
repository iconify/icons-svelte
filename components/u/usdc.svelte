<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f9-ia0b3w.css';
import '../../css/m/md286fbip.css';
import '../../css/v/vto4svfiq.css';
import '../../css/s/s0ju3ibka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="f9-ia0b3w"/><g class="md286fbip"><path class="vto4svfiq"/><path class="s0ju3ibka"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:usdc" {...props}></Icon>
