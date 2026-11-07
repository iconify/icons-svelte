<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn_f1tn5f.css';
import '../../css/g/gj0rcw2bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn_f1tn5f"/><path class="gj0rcw2bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:videocamera-bold-duotone" {...props}></Icon>
