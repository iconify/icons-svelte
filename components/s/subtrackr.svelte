<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_-dcbbxg.css';
import '../../css/b/b9nh0sb1l.css';
import '../../css/l/lv_7odbrh.css';
import '../../css/o/oct-20b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_-dcbbxg"/><path class="b9nh0sb1l"/><path class="lv_7odbrh"/><path class="oct-20b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:subtrackr" {...props}></Icon>
