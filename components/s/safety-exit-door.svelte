<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r6knjfq9q.css';
import '../../css/f/fxwmdgbgf.css';
import '../../css/k/kd35jjh2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r6knjfq9q"/><path class="fxwmdgbgf"/><path class="kd35jjh2h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:safety-exit-door" {...props}></Icon>
