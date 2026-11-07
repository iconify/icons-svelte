<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m22iwcsgw.css';
import '../../css/d/dg1dhqmqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m22iwcsgw"/><path class="dg1dhqmqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:server-path-bold-duotone" {...props}></Icon>
