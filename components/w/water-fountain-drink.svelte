<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gip4t6bed.css';
import '../../css/g/gdhs6pexy.css';
import '../../css/n/nrxmdfbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gip4t6bed"/><path class="gdhs6pexy"/><path class="nrxmdfbsh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:water-fountain-drink" {...props}></Icon>
