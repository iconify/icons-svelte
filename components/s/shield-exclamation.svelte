<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxnf2qx1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lxnf2qx1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:shield-exclamation" {...props}></Icon>
