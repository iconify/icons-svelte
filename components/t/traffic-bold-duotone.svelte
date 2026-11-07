<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_hji6de.css';
import '../../css/r/rhb1k3bmi.css';
import '../../css/i/il6nib2-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="rhb1k3bmi"/><path class="il6nib2-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:traffic-bold-duotone" {...props}></Icon>
