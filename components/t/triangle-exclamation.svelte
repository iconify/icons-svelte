<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj9tgdmli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uj9tgdmli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:triangle-exclamation" {...props}></Icon>
