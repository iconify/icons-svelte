<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crqpn7b-k.css';
import '../../css/c/c003gc-5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="crqpn7b-k"/><path class="c003gc-5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:unknown" {...props}></Icon>
