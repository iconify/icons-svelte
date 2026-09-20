<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw82srpqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pw82srpqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:valkey-light" {...props}></Icon>
