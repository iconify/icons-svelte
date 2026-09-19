<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owp543m0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="owp543m0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:wifi" {...props}></Icon>
