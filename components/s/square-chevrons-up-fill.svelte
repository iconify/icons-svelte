<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oybzxtbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oybzxtbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-chevrons-up-fill" {...props}></Icon>
