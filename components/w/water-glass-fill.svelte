<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duozttb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duozttb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:water-glass-fill" {...props}></Icon>
