<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/ca13g7t3o.css';
import '../../css/h/h78girq9f.css';
import '../../css/u/u54lry2-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ca13g7t3o"/><path class="h78girq9f"/><path class="u54lry2-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:strategy-business-success-peak" {...props}></Icon>
