<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_4bw_bzz.css';
import '../../css/i/i33fspbsl.css';
import '../../css/b/bns-mjpkf.css';
import '../../css/a/a2wenh5wd.css';
import '../../css/j/jrsejkkoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a_4bw_bzz"/><path class="i33fspbsl"/><path class="bns-mjpkf"/><path class="a2wenh5wd"/><path class="jrsejkkoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:snail-20-bold" {...props}></Icon>
