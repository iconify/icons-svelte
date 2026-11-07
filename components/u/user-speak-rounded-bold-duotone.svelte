<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om7lkbccu.css';
import '../../css/k/kw8vl3bjo.css';
import '../../css/s/smbj7_bwx.css';
import '../../css/l/lq3vbfrsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="om7lkbccu"/><path class="kw8vl3bjo"/><path class="smbj7_bwx"/><ellipse class="lq3vbfrsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-speak-rounded-bold-duotone" {...props}></Icon>
