<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gp0egaclj.css';
import '../../css/y/yxae7cq8q.css';
import '../../css/g/gset6gbkl.css';
import '../../css/l/l9rlr6fkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="gp0egaclj"/><path class="yxae7cq8q"/><path class="gset6gbkl"/><path class="l9rlr6fkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:vinyl-line-duotone" {...props}></Icon>
