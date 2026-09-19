<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz_smq6vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="jz_smq6vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:yarn" {...props}></Icon>
