<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6_lzt_ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k6_lzt_ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:triangle-down" {...props}></Icon>
