<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3gcr_bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x3gcr_bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:triangle-down-fill" {...props}></Icon>
