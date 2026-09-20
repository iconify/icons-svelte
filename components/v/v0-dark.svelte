<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnr7_ug-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hnr7_ug-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:v0-dark" {...props}></Icon>
