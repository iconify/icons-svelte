<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvaf9bcdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvaf9bcdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sorting-02" {...props}></Icon>
