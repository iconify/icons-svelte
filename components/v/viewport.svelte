<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avxsmbc0e.css';
import '../../css/t/tyy5pn3_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="avxsmbc0e"/><path class="tyy5pn3_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:viewport" {...props}></Icon>
