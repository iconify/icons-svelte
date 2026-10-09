<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3_6xbay.css';
import '../../css/w/w9clkgbaa.css';
import '../../css/b/bcto3bbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vm3_6xbay"/><path class="w9clkgbaa"/><path class="bcto3bbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whisk-48-bold" {...props}></Icon>
