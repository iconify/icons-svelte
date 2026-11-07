<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6bxffbta.css';
import '../../css/l/lh-_3in4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6bxffbta"/><path clip-rule="evenodd" class="lh-_3in4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-selection-outline" {...props}></Icon>
