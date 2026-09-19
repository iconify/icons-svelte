<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3shrqb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k3shrqb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:ruler" {...props}></Icon>
