<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/d/dyljlcr5k.css';
import '../../css/k/k3l1toopw.css';
import '../../css/j/jy9j1dbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dyljlcr5k"/><path class="k3l1toopw"/><path class="jy9j1dbzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wheelchair" {...props}></Icon>
