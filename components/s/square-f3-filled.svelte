<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3tdlwg3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3tdlwg3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-f3-filled" {...props}></Icon>
