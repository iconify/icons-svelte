<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6k0um.css';
import '../../css/a/a0m25c.css';
import '../../css/d/d1r5_v.css';
import '../../css/d/dk_amu.css';
import '../../css/r/r-from-0px.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="x6k0um"/><path class="a0m25c d1r5_v"/><path class="a0m25c dk_amu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:rss" {...props}></Icon>
