<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk-lxbcye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="sk-lxbcye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:shield-broken" {...props}></Icon>
