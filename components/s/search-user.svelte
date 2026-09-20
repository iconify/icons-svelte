<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/p4937g1yq.css';
import '../../css/e/etvrawbsd.css';
import '../../css/v/vlzselbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p4937g1yq"/><path class="etvrawbsd"/><path class="vlzselbkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:search-user" {...props}></Icon>
