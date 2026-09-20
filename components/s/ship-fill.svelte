<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqt3ewbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqt3ewbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ship-fill" {...props}></Icon>
