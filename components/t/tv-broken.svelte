<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lxfoi_psz.css';
import '../../css/z/zdx4gpbfd.css';
import '../../css/z/zmys6vjpk.css';
import '../../css/t/tar4ktbfi.css';
import '../../css/e/ewt7nk-fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lxfoi_psz"/><path class="zdx4gpbfd"/><path class="zmys6vjpk"/><path class="tar4ktbfi"/><path class="ewt7nk-fj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tv-broken" {...props}></Icon>
