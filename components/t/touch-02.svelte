<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbst9ofjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbst9ofjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:touch-02" {...props}></Icon>
