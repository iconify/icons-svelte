<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj4d1uf6r.css';
import '../../css/i/iscnj5bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qj4d1uf6r"/><path class="iscnj5bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:user-sleep" {...props}></Icon>
