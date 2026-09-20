<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-kqqwy_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-kqqwy_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:saudi-riyal" {...props}></Icon>
