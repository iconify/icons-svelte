<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf668zols.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tf668zols"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:thumbs-down" {...props}></Icon>
