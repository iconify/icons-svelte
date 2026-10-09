<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9k00b_1r.css';
import '../../css/w/wr4tv666r.css';
import '../../css/f/faz73x6ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u9k00b_1r"/><path class="wr4tv666r"/><path class="faz73x6ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:yen-20" {...props}></Icon>
