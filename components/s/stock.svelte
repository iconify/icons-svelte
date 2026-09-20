<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd6wzb_jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nd6wzb_jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:stock" {...props}></Icon>
