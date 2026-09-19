<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npyeo_9pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="npyeo_9pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:vault" {...props}></Icon>
