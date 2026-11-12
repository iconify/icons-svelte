<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj8_-65to.css';
import '../../css/l/lsqv2e_kf.css';
import '../../css/c/cf2gljolc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="xj8_-65to"/><path class="lsqv2e_kf"/><path class="cf2gljolc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shelfmark" {...props}></Icon>
