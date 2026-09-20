<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybmdpybot.css';
import '../../css/k/kdz4acc8r.css';
import '../../css/p/pogth7b8r.css';
import '../../css/s/s5gwvebwy.css';
import '../../css/z/zwjgx8kli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ybmdpybot"/><g class="kdz4acc8r"><path class="pogth7b8r"/><path class="s5gwvebwy"/><path class="zwjgx8kli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:teapot" {...props}></Icon>
