<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/c2qhvxbop.css';
import '../../css/y/yeh0umb4r.css';
import '../../css/d/dl30k4pxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c2qhvxbop"/><path class="yeh0umb4r"/><path class="dl30k4pxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wallet-02" {...props}></Icon>
