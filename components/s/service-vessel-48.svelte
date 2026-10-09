<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_h9q26nq.css';
import '../../css/y/yhqod3b-i.css';
import '../../css/v/vf1hj485a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x_h9q26nq"/><path class="yhqod3b-i"/><path class="vf1hj485a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:service-vessel-48" {...props}></Icon>
