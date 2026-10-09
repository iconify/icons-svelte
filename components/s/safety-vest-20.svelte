<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo04ejb3q.css';
import '../../css/t/tbxzsjbtj.css';
import '../../css/u/uz57xojdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xo04ejb3q"/><path class="tbxzsjbtj"/><path class="uz57xojdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:safety-vest-20" {...props}></Icon>
