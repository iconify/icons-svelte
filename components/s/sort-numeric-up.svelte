<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er_tio5vc.css';
import '../../css/g/gwgon2blw.css';
import '../../css/d/dn4_b_blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er_tio5vc"/><path class="gwgon2blw"/><path class="dn4_b_blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-numeric-up" {...props}></Icon>
