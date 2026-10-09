<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gikhi2gcs.css';
import '../../css/v/v10bzbf9m.css';
import '../../css/i/iw3d79bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gikhi2gcs"/><path class="v10bzbf9m"/><path class="iw3d79bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:substation-20-bold" {...props}></Icon>
