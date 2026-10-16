<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqk1cmb9r.css';
import '../../css/n/nqlwmj21u.css';
import '../../css/n/ne9n9bcpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vqk1cmb9r"/><path class="nqlwmj21u"/><path class="ne9n9bcpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-treatment-20-bold" {...props}></Icon>
