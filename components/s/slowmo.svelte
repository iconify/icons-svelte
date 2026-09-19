<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag96a_b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ag96a_b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:slowmo" {...props}></Icon>
