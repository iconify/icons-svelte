<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh__tacrr.css';
import '../../css/q/qhgqg5brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gh__tacrr"/><path class="qhgqg5brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:toolbox" {...props}></Icon>
