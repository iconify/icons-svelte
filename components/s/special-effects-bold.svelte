<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzjp4tb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qzjp4tb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:special-effects-bold" {...props}></Icon>
