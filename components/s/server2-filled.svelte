<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf5i7bcad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kf5i7bcad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:server2-filled" {...props}></Icon>
