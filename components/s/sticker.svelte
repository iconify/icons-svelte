<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9b2o80qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d9b2o80qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:sticker" {...props}></Icon>
