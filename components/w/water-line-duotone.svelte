<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/y/ym5aw5b8u.css';
import '../../css/s/smdkeehst.css';
import '../../css/r/rw7cyfbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ym5aw5b8u"/><path class="smdkeehst"/><path class="rw7cyfbex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:water-line-duotone" {...props}></Icon>
