<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-vpl2b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-vpl2b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:shield" {...props}></Icon>
