<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w-cyxxb1w.css';
import '../../css/q/qjy_z_buh.css';
import '../../css/x/xquh76ahq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="w-cyxxb1w"/><path class="qjy_z_buh"/><path class="xquh76ahq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:safety-fire-exit" {...props}></Icon>
