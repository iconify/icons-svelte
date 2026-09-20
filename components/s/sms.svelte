<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxi-o7b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bxi-o7b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sms" {...props}></Icon>
