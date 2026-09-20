<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_2inacgz.css';
import '../../css/l/lcg60_b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_2inacgz"/><path class="lcg60_b1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zil" {...props}></Icon>
