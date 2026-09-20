<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skvj_eznm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="skvj_eznm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:security-signal" {...props}></Icon>
