<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs-k6d3fm.css';
import '../../css/e/elvzx7mnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xs-k6d3fm"/><path class="elvzx7mnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ups-20-bold" {...props}></Icon>
