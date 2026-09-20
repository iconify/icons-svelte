<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/g/g_wfhb.css';
import '../../css/j/jin-gx.css';
import '../../css/d/d-0mee5h.css';
import '../../css/d/d-r5jj3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c g_wfhb"/><path class="a0m25c jin-gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:text-box-multiple-to-text-box-transition" {...props}></Icon>
