<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4ac0ub-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m4ac0ub-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:speedtest-tracker-light" {...props}></Icon>
