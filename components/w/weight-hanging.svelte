<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2mwuibgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e2mwuibgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:weight-hanging" {...props}></Icon>
