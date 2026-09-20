<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svkmrqn0y.css';
import '../../css/k/kybo6ib7m.css';
import '../../css/g/gbl_k3bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svkmrqn0y"/><path class="kybo6ib7m"/><path class="gbl_k3bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-id-duotone" {...props}></Icon>
