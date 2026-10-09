<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvskalk6x.css';
import '../../css/y/ychu0ub8d.css';
import '../../css/j/jy7ylib9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nvskalk6x"/><path class="ychu0ub8d"/><path class="jy7ylib9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rowing-20" {...props}></Icon>
