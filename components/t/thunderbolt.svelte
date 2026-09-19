<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqgya_hwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fqgya_hwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:thunderbolt" {...props}></Icon>
