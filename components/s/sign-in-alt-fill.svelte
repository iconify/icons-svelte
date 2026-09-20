<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpanu3zmm.css';
import '../../css/m/mqcc82bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpanu3zmm"/><path class="mqcc82bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:sign-in-alt-fill" {...props}></Icon>
