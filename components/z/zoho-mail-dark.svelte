<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffizjacec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ffizjacec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zoho-mail-dark" {...props}></Icon>
