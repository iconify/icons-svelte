<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_hh80boa.css';
import '../../css/p/p4pgybewu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v_hh80boa"/><path class="p4pgybewu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twenty-crm" {...props}></Icon>
