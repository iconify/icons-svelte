<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqxp1-bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uqxp1-bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:subscript" {...props}></Icon>
