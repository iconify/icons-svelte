<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd170tb4j.css';
import '../../css/x/xez906brx.css';
import '../../css/q/qtdg2bcei.css';
import '../../css/e/eua6i4aqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd170tb4j"/><path class="xez906brx"/><path class="qtdg2bcei"/><path class="eua6i4aqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vex" {...props}></Icon>
