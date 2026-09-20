<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4g0fs.css';
import '../../css/q/qa-o7h.css';
import '../../css/c/cjd4hj.css';
import '../../css/s/so-from-22.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4g0fs qa-o7h"/><path class="cjd4hj qa-o7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:valign-middle" {...props}></Icon>
