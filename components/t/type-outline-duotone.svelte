<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lup9ydbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lup9ydbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:type-outline-duotone" {...props}></Icon>
