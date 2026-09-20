<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj3hfzwqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj3hfzwqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:star-sharp-disabled" {...props}></Icon>
