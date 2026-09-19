<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxitz_43v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nxitz_43v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:wpbeginner" {...props}></Icon>
