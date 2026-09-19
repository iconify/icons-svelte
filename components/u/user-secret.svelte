<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynzxo5bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="ynzxo5bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:user-secret" {...props}></Icon>
