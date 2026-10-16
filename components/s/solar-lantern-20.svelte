<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii45op72q.css';
import '../../css/m/mfv2n_b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ii45op72q"/><path class="mfv2n_b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-lantern-20" {...props}></Icon>
