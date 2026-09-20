<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvtn-kbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvtn-kbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:settings-dot-sharp" {...props}></Icon>
