<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3evabc0f.css';
import '../../css/e/eojyj2bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w3evabc0f"/><path class="eojyj2bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:secondary-substation-20" {...props}></Icon>
