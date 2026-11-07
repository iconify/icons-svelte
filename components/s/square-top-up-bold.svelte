<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw3onyotj.css';
import '../../css/z/zfllz3bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw3onyotj"/><path class="zfllz3bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-top-up-bold" {...props}></Icon>
