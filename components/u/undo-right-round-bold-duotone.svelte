<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2wfgcisw.css';
import '../../css/n/nvyceb_wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i2wfgcisw"/><path class="nvyceb_wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-right-round-bold-duotone" {...props}></Icon>
