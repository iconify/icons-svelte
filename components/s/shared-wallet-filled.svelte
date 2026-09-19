<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpud8lb0h.css';
import '../../css/p/p8s23_l4e.css';
import '../../css/f/f66-habgz.css';
import '../../css/m/mpdz9zp2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wpud8lb0h"/><path class="p8s23_l4e"/><path clip-rule="evenodd" class="f66-habgz"/><path class="mpdz9zp2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:shared-wallet-filled" {...props}></Icon>
