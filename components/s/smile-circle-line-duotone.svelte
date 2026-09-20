<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/j/jty_abcpu.css';
import '../../css/s/so69kfbvn.css';
import '../../css/w/wbw_ixbrw.css';
import '../../css/y/yad62e0rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="jty_abcpu"/><path class="so69kfbvn"/><path class="wbw_ixbrw"/><ellipse class="yad62e0rw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smile-circle-line-duotone" {...props}></Icon>
