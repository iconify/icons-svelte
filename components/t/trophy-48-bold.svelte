<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqs1-cc1h.css';
import '../../css/n/n4lpjqt0r.css';
import '../../css/n/nqub7rbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vqs1-cc1h"/><path class="n4lpjqt0r"/><path class="nqub7rbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trophy-48-bold" {...props}></Icon>
