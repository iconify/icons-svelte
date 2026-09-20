<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1fcab9xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="m1fcab9xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:scuba-diving" {...props}></Icon>
