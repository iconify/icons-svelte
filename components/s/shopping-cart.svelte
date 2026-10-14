<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/k/kjz6ucc4j.css';
import '../../css/d/dmda8q39s.css';
import '../../css/e/er5tkr_vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="kjz6ucc4j"/><path class="dmda8q39s"/><path class="er5tkr_vy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:shopping-cart" {...props}></Icon>
