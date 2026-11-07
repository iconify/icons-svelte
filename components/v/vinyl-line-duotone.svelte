<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gp0egaclj.css';
import '../../css/m/mjwo7ebtq.css';
import '../../css/c/cs6wjacfk.css';
import '../../css/l/l9rlr6fkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="gp0egaclj"/><path class="mjwo7ebtq"/><path class="cs6wjacfk"/><path class="l9rlr6fkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:vinyl-line-duotone" {...props}></Icon>
