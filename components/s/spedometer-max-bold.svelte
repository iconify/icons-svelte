<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiy2c6lkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tiy2c6lkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:spedometer-max-bold" {...props}></Icon>
