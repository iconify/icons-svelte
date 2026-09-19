<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuxol8bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zuxol8bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:traffic-light" {...props}></Icon>
