<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvz35lkgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jvz35lkgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:tick" {...props}></Icon>
