<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6edjb7-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="a6edjb7-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:tick-small-solid" {...props}></Icon>
