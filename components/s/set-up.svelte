<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iubyquigk.css';
import '../../css/a/alzr3bc5d.css';
import '../../css/z/zvfnxjwub.css';
import '../../css/y/yzftjwb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iubyquigk"/><path class="alzr3bc5d"/><path class="zvfnxjwub"/><path class="yzftjwb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:set-up" {...props}></Icon>
