<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cofw0c4re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="cofw0c4re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sparkles" {...props}></Icon>
