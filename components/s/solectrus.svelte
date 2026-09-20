<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_1g5tbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_1g5tbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:solectrus" {...props}></Icon>
