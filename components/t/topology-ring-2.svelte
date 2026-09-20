<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkrm66bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkrm66bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:topology-ring-2" {...props}></Icon>
