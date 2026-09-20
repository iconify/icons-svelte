<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvrpevbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvrpevbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:user-check" {...props}></Icon>
