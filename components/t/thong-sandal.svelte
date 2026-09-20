<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtefmjolt.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/j/jzfxvzblz.css';
import '../../css/g/gz0i5bqap.css';
import '../../css/o/o-zxexbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jtefmjolt"/><g class="jn8qy4bru"><path class="jzfxvzblz"/><path class="gz0i5bqap"/><path class="o-zxexbtq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:thong-sandal" {...props}></Icon>
