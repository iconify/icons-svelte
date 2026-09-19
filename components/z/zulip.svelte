<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqnly8k0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iqnly8k0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:zulip" {...props}></Icon>
