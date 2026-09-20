<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/pyfr6rjow.css';
import '../../css/i/ibend16nn.css';
import '../../css/i/i21ar1oaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pyfr6rjow"/><path class="ibend16nn"/><path class="i21ar1oaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:three-square" {...props}></Icon>
