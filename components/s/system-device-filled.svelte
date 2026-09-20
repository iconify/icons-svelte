<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdrep3bvl.css';
import '../../css/z/zth91qbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdrep3bvl"/><path class="zth91qbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-device-filled" {...props}></Icon>
