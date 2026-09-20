<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj_f4vbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fj_f4vbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-profile-focus" {...props}></Icon>
