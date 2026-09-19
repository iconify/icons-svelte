<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7fum4b5a.css';
import '../../css/k/kv4jnr7fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7fum4b5a"/><path class="kv4jnr7fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:shield-x" {...props}></Icon>
