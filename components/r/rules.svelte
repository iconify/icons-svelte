<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdo2oulen.css';
import '../../css/n/nfkakzbeb.css';
import '../../css/q/qd5b0vbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hdo2oulen"/><path class="nfkakzbeb"/><path class="qd5b0vbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:rules" {...props}></Icon>
