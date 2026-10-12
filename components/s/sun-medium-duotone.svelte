<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mb3gk9bpt.css';
import '../../css/k/km9xy360q.css';
import '../../css/h/h7q3b_bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mb3gk9bpt"/><path class="km9xy360q"/><path class="h7q3b_bfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sun-medium-duotone" {...props}></Icon>
