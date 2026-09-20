<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-2h1_beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="h-2h1_beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:x-small-solid" {...props}></Icon>
