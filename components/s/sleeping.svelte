<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/qtp682b4j.css';
import '../../css/m/m7qhx_ojk.css';
import '../../css/c/cql1pwtbp.css';
import '../../css/g/gnr8u8brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qtp682b4j"/><path class="m7qhx_ojk"/><circle class="cql1pwtbp"/><path class="gnr8u8brg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sleeping" {...props}></Icon>
