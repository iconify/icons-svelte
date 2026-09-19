<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq0jxaclv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq0jxaclv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:tree-alt" {...props}></Icon>
