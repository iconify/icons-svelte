<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z5qk11bvl.css';
import '../../css/g/gvgnzkbfz.css';
import '../../css/f/f4hzekbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wm-k z5qk11bvl"/><path class="gvgnzkbfz wm-k"/><path class="f4hzekbll wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-anime:sigma" {...props}></Icon>
