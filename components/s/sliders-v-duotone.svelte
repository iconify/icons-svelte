<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiqh8os_h.css';
import '../../css/t/tgl2ebb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiqh8os_h"/><path class="tgl2ebb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:sliders-v-duotone" {...props}></Icon>
