<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wrmx9tb8s.css';
import '../../css/l/lnud8ybje.css';
import '../../css/w/w990p7q3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wrmx9tb8s"/><path class="lnud8ybje"/><path class="w990p7q3a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:subway-line" {...props}></Icon>
