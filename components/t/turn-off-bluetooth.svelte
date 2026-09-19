<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/m/m1lt5n8tk.css';
import '../../css/c/cq-p70qeo.css';
import '../../css/c/cr86h_b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="m1lt5n8tk"/><path class="cq-p70qeo"/><path class="cr86h_b7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:turn-off-bluetooth" {...props}></Icon>
