<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skmfgmluy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skmfgmluy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:usdt" {...props}></Icon>
