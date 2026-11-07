<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9pm6-j4k.css';
import '../../css/y/yepfcjb2n.css';
import '../../css/y/ym5h4t9sc.css';
import '../../css/q/q2ovdihlu.css';
import '../../css/n/ni_65ybtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9pm6-j4k"/><path class="yepfcjb2n"/><path class="ym5h4t9sc"/><path class="q2ovdihlu"/><path clip-rule="evenodd" class="ni_65ybtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wi-fi-router-round-bold" {...props}></Icon>
