<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho5eq6b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ho5eq6b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-skype" {...props}></Icon>
