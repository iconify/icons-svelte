<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtqh2o4ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gtqh2o4ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:tag-ruble" {...props}></Icon>
