<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/audsjhv2z.css';
import '../../css/k/k6wji4t4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="audsjhv2z"/><path class="k6wji4t4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:sort-ascending" {...props}></Icon>
