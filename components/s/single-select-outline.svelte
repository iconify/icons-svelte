<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlu9gyjbu.css';
import '../../css/t/t54ht8bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlu9gyjbu"/><path class="t54ht8bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:single-select-outline" {...props}></Icon>
