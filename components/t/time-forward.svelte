<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu5aiccfe.css';
import '../../css/v/vctjzdmxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nu5aiccfe"/><path class="vctjzdmxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:time-forward" {...props}></Icon>
