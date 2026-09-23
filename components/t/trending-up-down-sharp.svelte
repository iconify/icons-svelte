<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2e8exbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2e8exbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:trending-up-down-sharp" {...props}></Icon>
