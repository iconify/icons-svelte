<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceonq4b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="ceonq4b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:status-alert" {...props}></Icon>
