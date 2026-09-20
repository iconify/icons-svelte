<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-73ullsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g-73ullsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-hotel-bell-service-concierge-porter-call-ring-bellhop-bell-reception" {...props}></Icon>
