<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw9j0hl2o.css';
import '../../css/y/ygse80efx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw9j0hl2o"/><path class="ygse80efx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:uninstall-filled" {...props}></Icon>
