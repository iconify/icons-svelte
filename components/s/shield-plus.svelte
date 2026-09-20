<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1hrasbfn.css';
import '../../css/k/kl1808iyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1hrasbfn"/><path class="kl1808iyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:shield-plus" {...props}></Icon>
