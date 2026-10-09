<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbnoic5rd.css';
import '../../css/m/m-8nc9b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lbnoic5rd"/><path class="m-8nc9b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:save-20" {...props}></Icon>
