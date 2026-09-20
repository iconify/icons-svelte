<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he_-2_omg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="he_-2_omg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:trophy" {...props}></Icon>
