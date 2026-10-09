<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iekkhobgo.css';
import '../../css/a/ahhgx2b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iekkhobgo"/><path class="ahhgx2b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:traffic-light-48-bold" {...props}></Icon>
