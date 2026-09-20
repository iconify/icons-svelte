<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/qbo-06bir.css';
import '../../css/p/ps3-lcbfd.css';
import '../../css/b/b281nlban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qbo-06bir"/><path class="ps3-lcbfd"/><path class="b281nlban"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:skating-1" {...props}></Icon>
