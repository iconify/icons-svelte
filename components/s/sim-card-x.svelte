<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fde37bbhy.css';
import '../../css/g/gor42-b7e.css';
import '../../css/v/vrb4d8bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="fde37bbhy"/><path class="gor42-b7e"/><path class="vrb4d8bnb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:sim-card-x" {...props}></Icon>
