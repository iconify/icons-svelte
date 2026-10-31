<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0b1pobvd.css';
import '../../css/n/nxk669c7l.css';
import '../../css/g/g147opbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<g display="block"><path class="b0b1pobvd"/><path class="nxk669c7l"/><path class="g147opbuc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:tofu" {...props}></Icon>
