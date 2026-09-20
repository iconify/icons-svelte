<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_xqph0yx.css';
import '../../css/c/clz-rp4dm.css';
import '../../css/b/by7c5-bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_xqph0yx"/><path class="clz-rp4dm"/><rect class="by7c5-bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:wallet-alt-duotone" {...props}></Icon>
