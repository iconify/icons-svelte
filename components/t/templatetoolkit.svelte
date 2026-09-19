<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2x8u-v_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o2x8u-v_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:templatetoolkit" {...props}></Icon>
