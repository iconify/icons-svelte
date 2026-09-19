<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp471zbxk.css';
import '../../css/z/z53wpybvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp471zbxk"/><path class="z53wpybvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:virus" {...props}></Icon>
