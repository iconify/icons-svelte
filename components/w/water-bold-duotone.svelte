<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9lkykbai.css';
import '../../css/p/pj1dodgri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9lkykbai"/><path class="pj1dodgri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:water-bold-duotone" {...props}></Icon>
