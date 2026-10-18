<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqep3ob2t.css';
import '../../css/p/pvryphb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fqep3ob2t"/><path class="pvryphb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seaweed-48-bold" {...props}></Icon>
