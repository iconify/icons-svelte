<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh8cl0c0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jh8cl0c0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:top-right-solid" {...props}></Icon>
