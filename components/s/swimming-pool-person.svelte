<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n9l5e8mcr.css';
import '../../css/a/a-ewrneoj.css';
import '../../css/r/r6v1ktpdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n9l5e8mcr"/><path class="a-ewrneoj"/><path class="r6v1ktpdr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:swimming-pool-person" {...props}></Icon>
