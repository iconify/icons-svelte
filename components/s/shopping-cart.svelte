<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj3h9ft4y.css';
import '../../css/d/d2x1331fj.css';
import '../../css/u/uii4avzkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lj3h9ft4y"/><circle class="d2x1331fj"/><circle class="uii4avzkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:shopping-cart" {...props}></Icon>
