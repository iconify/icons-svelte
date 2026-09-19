<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xvhpxbc1d.css';
import '../../css/k/k0soy3mpv.css';
import '../../css/u/ua7h0o40v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="xvhpxbc1d"/><path class="k0soy3mpv"/><circle class="ua7h0o40v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:wallet-one" {...props}></Icon>
