<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgmleib2q.css';
import '../../css/l/lw9-dbcju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vgmleib2q"/><path class="lw9-dbcju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:terraced-house-48-bold" {...props}></Icon>
