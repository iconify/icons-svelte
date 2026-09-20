<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay1_04bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ay1_04bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:spinner2" {...props}></Icon>
