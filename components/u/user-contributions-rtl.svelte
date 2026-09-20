<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkto-2bwr.css';
import '../../css/x/x_lnf_bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bkto-2bwr"/><circle class="x_lnf_bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-contributions-rtl" {...props}></Icon>
