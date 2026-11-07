<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuc6r60rn.css';
import '../../css/m/m041_sk4u.css';
import '../../css/y/yp1-ku-9n.css';
import '../../css/m/mvaxu_b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuc6r60rn"/><path class="m041_sk4u"/><path class="yp1-ku-9n"/><path class="mvaxu_b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-fall-bold" {...props}></Icon>
