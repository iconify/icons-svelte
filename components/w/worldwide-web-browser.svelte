<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/v/v1hug_bsz.css';
import '../../css/s/s6i8zk-5y.css';
import '../../css/l/l5_dd4bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="v1hug_bsz"/><path class="s6i8zk-5y"/><path class="l5_dd4bsw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:worldwide-web-browser" {...props}></Icon>
