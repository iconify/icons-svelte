<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb29_fb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kb29_fb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:triangle" {...props}></Icon>
