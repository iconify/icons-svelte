<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/owfbcdrve.css';
import '../../css/x/xacu93d6a.css';
import '../../css/k/kg1skkbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="owfbcdrve"/><path class="xacu93d6a"/><path class="kg1skkbwt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:saving-bank" {...props}></Icon>
