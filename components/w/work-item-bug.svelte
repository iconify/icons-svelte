<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tihe0h5no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tihe0h5no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:work-item-bug" {...props}></Icon>
