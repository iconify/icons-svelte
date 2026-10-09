<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je7r7lbpm.css';
import '../../css/j/jy5mj2b4j.css';
import '../../css/v/veivehbuo.css';
import '../../css/u/ug19bk4co.css';
import '../../css/p/p70a5nd2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="je7r7lbpm"/><path class="jy5mj2b4j"/><path class="veivehbuo"/><path class="ug19bk4co"/><path class="p70a5nd2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:turbine-maintenance-20-bold" {...props}></Icon>
