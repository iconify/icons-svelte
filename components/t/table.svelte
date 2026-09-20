<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4hkjobnc.css';
import '../../css/m/moe9y6t0w.css';
import '../../css/g/g62bnqbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4hkjobnc"/><path class="moe9y6t0w"/><path class="g62bnqbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:table" {...props}></Icon>
