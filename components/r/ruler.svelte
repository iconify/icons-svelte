<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd6nirbah.css';
import '../../css/y/yjey4tfxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nd6nirbah"/><path class="yjey4tfxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:ruler" {...props}></Icon>
