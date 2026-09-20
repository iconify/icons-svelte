<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au0ie6bpn.css';
import '../../css/l/l4ovptbip.css';
import '../../css/q/qkmfhjfvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="au0ie6bpn"/><path class="l4ovptbip"/><path class="qkmfhjfvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:stop-cog" {...props}></Icon>
