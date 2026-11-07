<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itcl84bfm.css';
import '../../css/m/mzfoi9l1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itcl84bfm"/><path clip-rule="evenodd" class="mzfoi9l1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-right-square-outline" {...props}></Icon>
