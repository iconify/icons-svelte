<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf4wyfbwq.css';
import '../../css/o/or5-kgblm.css';
import '../../css/q/qswqrgbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yf4wyfbwq"/><path class="or5-kgblm"/><path class="qswqrgbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-dropbox-outline" {...props}></Icon>
