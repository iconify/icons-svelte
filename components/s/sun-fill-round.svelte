<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkkqx5jfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkkqx5jfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sun-fill-round" {...props}></Icon>
