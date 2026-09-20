<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li-jbvb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="li-jbvb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:scale-unbalance" {...props}></Icon>
