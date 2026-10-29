<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/lt5xwl8wq.css';
import '../../css/v/vze4wuf6n.css';
import '../../css/c/c21i8ub3b.css';
import '../../css/c/cjoi-wios.css';
import '../../css/q/qr4ochb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="lt5xwl8wq wm-deco"/><path class="vze4wuf6n wm-deco"/><path class="c21i8ub3b wm-k"/><path class="cjoi-wios wm-a"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:video-off-blueprint" {...props}></Icon>
