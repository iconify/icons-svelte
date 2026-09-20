<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnt0b3bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qnt0b3bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:saguaro" {...props}></Icon>
