<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/g/gzks8bcyr.css';
import '../../css/w/wso75kn4e.css';
import '../../css/x/x2jzcbboy.css';
import '../../css/s/sarx32axf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="gzks8bcyr"/><circle class="wso75kn4e"/><path class="x2jzcbboy"/><path class="sarx32axf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:timed-mail" {...props}></Icon>
