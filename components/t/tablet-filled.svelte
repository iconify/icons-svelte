<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bojbs1zxp.css';
import '../../css/t/tuobqqwah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bojbs1zxp"/><path class="tuobqqwah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tablet-filled" {...props}></Icon>
