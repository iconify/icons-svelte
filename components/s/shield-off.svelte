<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-6k-cc3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-6k-cc3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shield-off" {...props}></Icon>
